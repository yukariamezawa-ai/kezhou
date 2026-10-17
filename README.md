<div align="center">

<img src="assets/icon.png" width="128" height="128" alt="Lumen KeZhou Logo" />

# Lumen · 刻舟浏览器
### 新一代 AI 视觉灵感探索、分镜秒级采摘与私密媒体存档套件

[![Release](https://img.shields.io/github/v/release/yukariamezawa-ai/kezhou?style=for-the-badge&color=blue&logo=github)](https://github.com/yukariamezawa-ai/kezhou/releases/latest)
[![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/yukariamezawa-ai/kezhou/releases/latest)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-orange?style=for-the-badge&logo=gnu)](LICENSE)
[![Security: SQLCipher](https://img.shields.io/badge/Security-SQLCipher%20256-green?style=for-the-badge&logo=sqlite)](https://github.com/yukariamezawa-ai/kezhou)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen?style=for-the-badge)](https://github.com/yukariamezawa-ai/kezhou/releases)

<p align="center">
  <b>沉浸探索</b> • <b>0ms秒采</b> • <b>运镜打标</b> • <b>加密私密库</b> • <b>防随手翻看</b>
</p>

[下载最新 APK](https://github.com/yukariamezawa-ai/kezhou/releases/latest) • [核心特性](#-核心特性) • [界面预览](#-应用预览) • [安全与威胁模型](#-安全边界与威胁模型) • [部署指南](#-轻量云端部署)

---

</div>

## 📱 应用预览

<div align="center">
  <table>
    <tr>
      <td align="center" width="20%">
        <b>1. AI 社区与灵感探索</b><br/>
        <img src="assets/screenshots/01_explore_home.png" width="100%" alt="探索首页" />
      </td>
      <td align="center" width="20%">
        <b>2. 灵感瀑布流与私密库</b><br/>
        <img src="assets/screenshots/02_inspo_board.png" width="100%" alt="灵感板" />
      </td>
      <td align="center" width="20%">
        <b>3. 免费体验与卡密激活</b><br/>
        <img src="assets/screenshots/03_quota_license.png" width="100%" alt="配额弹窗" />
      </td>
      <td align="center" width="20%">
        <b>4. 诱饵计算器伪装层</b><br/>
        <img src="assets/screenshots/04_decoy_disguise.png" width="100%" alt="计算器伪装" />
      </td>
      <td align="center" width="20%">
        <b>5. 镜头参数与离线存档</b><br/>
        <img src="assets/screenshots/05_shot_detail.png" width="100%" alt="分镜详情" />
      </td>
    </tr>
  </table>
</div>

---

## 🌟 核心特性

### 🎬 1. AI 灵感社区直达与秒级采摘
- **原生传送门**：主页内置 Sora、Runway、可灵 (Kling)、Civitai 等主流社区与运镜标签快筛；
- **0ms 胶囊秒采**：在探索页或任意网页播放视频时，点击右上角「捕获灵感」胶囊，0 延迟呼出打标面板，自动抽取高清封面、作者与标题；
- **提示词工坊（Prompt Studio）**：为分镜快速注入电影级运镜词（`+推镜头`、`+变焦`、`+丁达尔光`、`+赛博朋克`），支持一键格式化导出 Prompt 流转至 Midjourney、Runway、可灵。

### 🛡️ 2. KuroBox 私密媒体保险箱
- **SQLCipher 全库加密**：用户收藏、AI 提示词与私密元数据经由底层 AES-256 加密存储；
- **系统相册隔离**：离线视频与音频独立写入应用沙箱私有空间，配合 `.nomedia` 守卫，**系统相册、媒体扫描器与普通文件管理器完全无法索引**；
- **通知栏脱敏防护**：离线进度在通知栏仅显示百分比与中性状态词，绝不泄露任何视频标题、链接或封面。

### 🎭 3. 随手翻看免疫与多级伪装
- **纯净浏览器外表**：桌面图标与应用名呈现为标准创作探索浏览器，主界面零任何敏感词汇；
- **隐藏暗门直达**：在地址栏输入 `kezhou://vault` 或在设置界面连点 5 次版本号即可进入隐藏媒体库；
- **诱饵锁屏集成**：支持无缝启用诱饵计算器伪装，输入专属暗号 PIN 码方可进入真实面板。

### 💎 4. 终端离线配额与授权鉴权
- **低门槛免费试用**：每台终端原生享有 **10 次** 免费离线保存与存档体验；
- **灵活卡密升级**：配额耗尽后支持一键输入卡密解锁无限存储特权；
- **云端与离线双模容灾**：支持接入 Cloudflare Workers（每天 10 万次免费调用）实现全球云端核销，网络离线时本地自动安全降级。

---

## 📥 下载安装

| 安装包 (APK) | 适用芯片架构 | 推荐场景 | 安装包大小 | 下载直链 |
| :--- | :--- | :--- | :--- | :--- |
| **`KeZhou-1.9.0-arm64-v8a-release-github.apk`** | **arm64-v8a** | **强烈推荐（95% 现代安卓手机）** | **~66.9 MB** | [点击下载](https://github.com/yukariamezawa-ai/kezhou/releases/download/v1.9.0/KeZhou-1.9.0-arm64-v8a-release-github.apk) |
| `KeZhou-1.9.0-universal-release-github.apk` | 全部架构一体包 | 兼容未知或全部机型 | ~207.0 MB | [点击下载](https://github.com/yukariamezawa-ai/kezhou/releases/download/v1.9.0/KeZhou-1.9.0-universal-release-github.apk) |
| `KeZhou-1.9.0-armeabi-v7a-release-github.apk` | armeabi-v7a | 老旧 32 位安卓机型 | ~56.3 MB | [点击下载](https://github.com/yukariamezawa-ai/kezhou/releases/download/v1.9.0/KeZhou-1.9.0-armeabi-v7a-release-github.apk) |
| `KeZhou-1.9.0-x86_64-release-github.apk` | x86_64 | PC 安卓模拟器 / ChromeOS | ~62.1 MB | [点击下载](https://github.com/yukariamezawa-ai/kezhou/releases/download/v1.9.0/KeZhou-1.9.0-x86_64-release-github.apk) |

> 校验完整性（SHA-256）：  
> `2BC092EB96B69C3D90E300F1136295EF00CE48F2538576CF369D7F0A561F06BF`（arm64-v8a）

---

## 🔒 安全边界与威胁模型

为了保证信息透明与用户知情权，刻舟坚持诚实披露安全边界：

- ✅ **防得住：随手翻看手机的人**  
  手机借给朋友/同事时，桌面图标、主界面菜单无任何异常，相册与文件管理器检索不到任何已保存媒体，通知栏无内容泄露。
- ⚠️ **部分防住：拿到已解锁手机且懂行的人**  
  不知道 `kezhou://vault` 暗门指令与版本号连击触发点的人无法找到入口；建议在设置中开启「诱饵计算器锁」进一步防范。
- ❌ **不防：专业物理取证与 Root 提权**  
  离线媒体存储于 Android 应用私有沙箱路径，未进行多重分块切片加密，具备 Root 权限或专业取证设备可以直接通过底层提取。

---

## ☁️ 轻量云端部署 (Cloudflare Workers)

本项目自带完整的 0 成本服务端脚本，用于终端 10 次配额管理与卡密发售核销：

1. 打开 [Cloudflare 控制台](https://dash.cloudflare.com/)；
2. 新建 KV 命名空间 `QUOTA_KV`；
3. 新建 Worker 并粘贴本项目中的 `cloudflare-worker/worker.js` 代码；
4. 绑定 KV 即可获得高可用无服务器后端，每天 100,000 次请求免费。

管理员可通过一行命令批量生成卡密并导入自动发货平台：
```bash
curl -X POST https://your-worker.workers.dev/api/admin/generate-keys \
  -H "Authorization: Bearer your_admin_secret" \
  -d '{"count": 50, "prefix": "KB"}'
```

---

## 📜 开源许可与致敬

- 本项目基于开源项目 **YTDLnis** 深度衍生重构，底层使用强大通用的 **yt-dlp** 媒体解析框架。
- 遵循 **GNU General Public License v3.0 (GPLv3)** 开源协议。
- 本项目旨在为 AI 创作者提供本地化的灵感整理与私密存档解决方案，严禁用于任何侵犯版权或违反平台服务条款的非法用途。
