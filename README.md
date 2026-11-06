<div align="center">

# WinCast

### 下一代多智能体协同开发工作台与 AI 自动化平台
**Next-Generation Multi-Agent Workspace & AI Automation Platform**

[![Release](https://img.shields.io/github/v/release/yibeixiaobai/wincast?color=blue&style=flat-square)](https://github.com/yibeixiaobai/wincast/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey?style=flat-square)](#-下载安装包-downloads)
[![License](https://img.shields.io/badge/license-Apache--2.0-green?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/yibeixiaobai/wincast?style=flat-square)](https://github.com/yibeixiaobai/wincast/stargazers)

<p align="center">
  <a href="#-简介-introduction">简介</a> •
  <a href="#-核心特性-key-features">核心特性</a> •
  <a href="#-下载安装包-downloads">下载安装</a> •
  <a href="#-cli--tui-终端模式">终端模式</a> •
  <a href="#-架构概览-architecture-overview">架构概览</a> •
  <a href="#-常见问题-faq">常见问题</a>
</p>

</div>

---

## 📖 简介 (Introduction)

**WinCast** 是一款面向多平台 AI 协同开发、社媒矩阵自动化与多端操作赋能的现代工作台。通过融合**原生桌面端（Desktop App）**、**极客终端界面（TUI）**、**轻量免安装 Web 端** 以及底层的 **WinCode Agent 运行时**，WinCast 打造了一整套软硬一体、高并发、安全可信的智能编程与任务执行环境。

无论你是需要强大的计算机视觉操作智能体（Computer-Using Agent），还是在多智能体并发网络中进行复杂代码工程重构，WinCast 均能提供流畅、沉浸且稳定的工作流体验。

---

## ✨ 核心特性 (Key Features)

- 🖥️ **跨平台原生桌面工作台**：深度适配 Windows 10/11、macOS（全面支持 Apple Silicon M1~M4 及 Intel 架构）与各大主流 Linux 发行版，提供极致流畅的原生体验。
- 🤖 **集群智能体与多任务并行**：支持 Master-Worker 架构的多智能体协同，任务隔离、状态自愈、无限画布协同，助力长时复杂任务高效推进。
- 💻 **多形态运行入口 (Zero-Electron)**：除桌面应用外，支持直接在终端启动原生交互式 TUI 或通过 `--web` 启动轻量浏览器界面，轻量极客，随时随地接入。
- 🔄 **受控动态更新与差量升级**：基于 GitHub Releases 构建的受控更新体系，支持小版本前端热更（秒级刷新）与大版本安装包差量无感自动升级。
- 🛡️ **工业级安全防伪与运行保护**：内置官方 RS256 证书数字签名与哈希自检，从底层杜绝核心代码与执行载荷被篡改。

---

## 🚀 下载安装包 (Downloads)

所有安装包均已由官方 CI/CD 流水线自动化构建并附加数字签名，欢迎前往 [Releases 页面](https://github.com/yibeixiaobai/wincast/releases/latest) 获取最新版本：

### 最新正式版：**v1.0.0**

| 操作系统 / 硬件架构 | 安装包格式 | 文件大小 | 官方直连下载 | 国内加速下载 (免翻镜像) |
| :--- | :--- | :--- | :--- | :--- |
| **Windows x64** | `.exe` (NSIS 安装包) | ~167 MB | [下载 .exe](https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-win-x64.exe) | [加速下载](https://ghfast.top/https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-win-x64.exe) |
| **macOS Apple Silicon** (M1/M2/M3/M4) | `.dmg` 挂载镜像 | ~208 MB | [下载 arm64 .dmg](https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-mac-arm64.dmg) | [加速下载](https://ghfast.top/https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-mac-arm64.dmg) |
| **macOS Apple Silicon** (绿色归档) | `.zip` 压缩包 | ~201 MB | [下载 arm64 .zip](https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-mac-arm64.zip) | [加速下载](https://ghfast.top/https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-mac-arm64.zip) |
| **macOS Intel x64** | `.dmg` 挂载镜像 | ~213 MB | [下载 x64 .dmg](https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-mac-x64.dmg) | [加速下载](https://ghfast.top/https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-mac-x64.dmg) |
| **macOS Intel x64** (绿色归档) | `.zip` 压缩包 | ~206 MB | [下载 x64 .zip](https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-mac-x64.zip) | [加速下载](https://ghfast.top/https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-mac-x64.zip) |
| **Linux (通用免安装)** | `.AppImage` | ~215 MB | [下载 .AppImage](https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-linux-x86_64.AppImage) | [加速下载](https://ghfast.top/https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-linux-x86_64.AppImage) |
| **Linux (Ubuntu / Debian)** | `.deb` | ~160 MB | [下载 .deb](https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-linux-amd64.deb) | [加速下载](https://ghfast.top/https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-linux-amd64.deb) |
| **Linux (RHEL / CentOS / Fedora)** | `.rpm` | ~126 MB | [下载 .rpm](https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-linux-x86_64.rpm) | [加速下载](https://ghfast.top/https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-linux-x86_64.rpm) |
| **Linux (Arch Linux)** | `.pkg.tar.zst` | ~141 MB | [下载 .pkg.tar.zst](https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-linux-x64.pkg.tar.zst) | [加速下载](https://ghfast.top/https://github.com/yibeixiaobai/wincast/releases/download/v1.0.0/WinCast-1.0.0-linux-x64.pkg.tar.zst) |

---

## 🛠️ CLI / TUI 终端模式

除了完整的 Electron 桌面安装包外，WinCast 提供了独立的命令行运行时，支持无图形桌面环境的服务器或极客终端：

```bash
# 进入终端交互式 TUI 界面
wincast

# 启动 Web 界面服务并在本地浏览器打开
wincast --web

# 指定工作区目录与监听端口
wincast --web --workspace /path/to/project --port 3030

# 查看完整帮助说明
wincast --help
```

---

## 🏗️ 架构概览 (Architecture Overview)

```
┌────────────────────────────────────────────────────────┐
│                   WinCast Workspace                    │
├──────────────────────────┬─────────────────────────────┤
│   Desktop Host (Electron)│    Web Client & Terminal TUI│
├──────────────────────────┴─────────────────────────────┤
│           Bidirectional RPC / IPC Protocol             │
├────────────────────────────────────────────────────────┤
│           WinCode Agent Core & Multi-Agent Matrix      │
├──────────────────────────┬─────────────────────────────┤
│  Browser Automation (CDP)│  Computer-Use (CUA Native)  │
├──────────────────────────┴─────────────────────────────┤
│  Update Policy Guard & Digital Signature Verification  │
└────────────────────────────────────────────────────────┘
```

---

## ❓ 常见问题 (FAQ)

<details>
<summary><b>Q1: macOS 安装打开时提示「已损坏」或「无法打开，因为无法验证开发者」？</b></summary>

这是 macOS Gatekeeper 对未签署 Apple 开发者商业证书软件的默认安全策略。在终端中执行以下命令去除安全隔离标记即可：
```bash
sudo xattr -rd com.apple.quarantine /Applications/WinCast.app
```
</details>

<details>
<summary><b>Q2: Linux 下 AppImage 如何运行？</b></summary>

下载后添加可执行权限即可直接运行：
```bash
chmod +x WinCast-1.0.0-linux-x86_64.AppImage
./WinCast-1.0.0-linux-x86_64.AppImage
```
</details>

<details>
<summary><b>Q3: 客户端如何进行后续更新？</b></summary>

WinCast 具备内置的自动更新器（Auto Updater）与动态策略网关。启动时会自动检测新版本并支持静默下载、增量差量升级，无需每次手动重新下载完整安装包。
</details>

---

## 📄 开源许可证 (License)

本项目采用 [Apache-2.0 License](LICENSE) 开源许可证。
