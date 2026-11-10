<div align="center">
  <img src="https://raw.githubusercontent.com/ywgf88/ywgf88/main/banner-ride.svg" width="100%" alt="ywgf88 — 白天骑行 / 晚上折腾路由器" />

  <p><b>中文</b> · <a href="#english">English</a></p>
</div>

## 关于我

白天骑行：在绿道、在公园、在马路上，跟大自然和阳光打交道，顺路看武汉的街道和变化。
晚上做实验：把路由器和固件当成玩具，反复刷机、改配置、修编译坑。

从 2018 年注册 GitHub 起，这里一直是我的草稿纸。现在主要折腾三件事：

- **固件云编译** — 用 GitHub Actions 维护 ImmortalWrt 25.12 的 x86_64 与 MT7981 两条流水线，调插件、改 rootfs 大小、修那些只有编译到一半才会出现的坑。
- **软路由落地** — Passwall2、主题、`uci-defaults`，目标是刷完机插上就能用，不用再补一堆手动步骤。
- **自托管与自动化** — Docker 起服务，Python 写小脚本替自己做重复的事，跑通就丢在后台。

> 一个朴素的偏好：重复的事交给脚本，踩过的坑写成文档。

<div align="center">

![OpenWrt](https://img.shields.io/badge/OpenWrt-25.12-00A9E0?style=flat-square&logo=openwrt&logoColor=white)
![ImmortalWrt](https://img.shields.io/badge/ImmortalWrt-x86_64-2C8EBB?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-云编译-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Proxmox VE](https://img.shields.io/badge/Proxmox%20VE-E57000?style=flat-square&logo=proxmox&logoColor=white)

</div>

## 手头的仓库

| 仓库 | 说明 |
| :--- | :--- |
| [**Actions-ImmortalWrt-X86**](https://github.com/ywgf88/Actions-ImmortalWrt-X86) | ImmortalWrt `openwrt-25.12` x86_64 云编译模板，25.12.2 / IPv4 / rootfs 1G |
| [**Actions-OpenWrt-MT7981**](https://github.com/ywgf88/Actions-OpenWrt-MT7981) | MT7981 平台的 25.12.2 固件：CMCC RAX3000M、360 T7 |
| [**Actions-OpenWrt-X86**](https://github.com/ywgf88/Actions-OpenWrt-X86) | 基于 P3TERX 模板改造的 x86 固件流水线 |
| [**openwrt-action-ct3003**](https://github.com/ywgf88/openwrt-action-ct3003) | CT3003 自用固件，长期维护的那一份 |

<sub>其余仓库多是 issue 级别的关注与 fork：Kwrt、ImmortalWrt-ImageBuilder、TrendRadar、aerial-tv…… 看到有意思的就拉下来跑一遍。</sub>

## 一点数据

<div align="center">

![Followers](https://img.shields.io/github/followers/ywgf88?style=for-the-badge&labelColor=0A1626&color=33C6FF&logo=github&logoColor=white)

<sub>20 个公开仓库 · Shell 为主，Python 为辅，大部分今年还在更新。</sub>

</div>

---

## English

<div align="center">
  <img src="https://raw.githubusercontent.com/ywgf88/ywgf88/main/banner-ride-en.svg" width="100%" alt="ywgf88 — ride by day, flash by night" />
</div>

By day I ride — greenways, parks, and the streets of Wuhan, chasing daylight and watching how the city shifts block by block.
By night I treat routers and firmware as a lab: flashing, reconfiguring, and chasing compile errors until the image finally boots.

I signed up on GitHub back in 2018 and have used it as a scratchpad ever since. Three things take most of my time now:

- **Firmware builds in the cloud** — GitHub Actions pipelines for ImmortalWrt 25.12 on both x86_64 and MT7981: swapping plugins, resizing rootfs, and fixing the bugs that only surface halfway through a build.
- **Soft-router setups** — Passwall2, themes, `uci-defaults`. The goal is simple: flash the image, plug it in, and everything works without a pile of manual steps afterwards.
- **Self-hosting and automation** — Docker for services, small Python scripts for the repetitive parts. Write it once, let it run in the background.

> A simple preference: let scripts do the repetitive work, and write down every pit I fall into.

## What's on the bench

| Repo | What it is |
| :--- | :--- |
| [**Actions-ImmortalWrt-X86**](https://github.com/ywgf88/Actions-ImmortalWrt-X86) | ImmortalWrt `openwrt-25.12` x86_64 build template — 25.12.2 / IPv4 / 1G rootfs |
| [**Actions-OpenWrt-MT7981**](https://github.com/ywgf88/Actions-OpenWrt-MT7981) | OpenWrt 25.12.2 images for MT7981 boards: CMCC RAX3000M and 360 T7 |
| [**Actions-OpenWrt-X86**](https://github.com/ywgf88/Actions-OpenWrt-X86) | x86 build pipeline adapted from the P3TERX template |
| [**openwrt-action-ct3003**](https://github.com/ywgf88/openwrt-action-ct3003) | My long-running daily-driver build for the CT3003 |

<sub>The rest are issues-worth of interest and forks: Kwrt, ImmortalWrt-ImageBuilder, TrendRadar, aerial-tv… if it looks interesting, I pull it down and run it.</sub>

## Numbers

<div align="center">

<sub>20 public repos · mostly Shell, a little Python · most of them still updated this year.</sub>

</div>

Everything here is a working note, not a product. If a repo saves you an hour, an issue is welcome.

<p><a href="#关于我">↑ Back to the Chinese version</a></p>

<div align="center">

<img src="https://raw.githubusercontent.com/ywgf88/ywgf88/main/logo.svg" width="88" alt="ywgf88 logo" />

<sub>Wuhan, China — on GitHub since 2018</sub>

</div>