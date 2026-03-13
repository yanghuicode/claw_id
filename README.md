# claw_id - AI Identity Configuration

<p align="center">
  <img src="01.jpg" alt="OpenClaw Logo" width="200">
</p>

一个用于配置 AI Agent 身份、灵魂和用户信息的工具集。

## 🦞 项目说明

这是一个为 AI Agent (OpenClaw) 设计的身份配置管理系统，包含三个核心配置文件：

| 文件 | 说明 |
|------|------|
| `SOUL.md` | 定义 AI 的核心信念、边界、风格和连续性 |
| `IDENTITY.md` | 定义 AI 的名称、类型、风格、表情符号和头像 |
| `USER.md` | 记录用户的基本信息、上下文和偏好 |

## 🎮 在线编辑器

项目提供了一个复古风格的配置编辑器 `config-editor.html`，支持：

- 实时预览配置内容
- 多标签页编辑（灵魂 / 身份 / 用户）
- 复制配置到剪贴板
- 从现有文件自动加载数据
- 本地存储活动标签页状态

直接在浏览器中打开 [config-editor.html](config-editor.html) 即可开始编辑。

## 📁 项目结构

```
soul_hub/
├── config-editor.html  # 配置编辑器（HTML/CSS/JS）
├── SOUL.md            # AI 灵魂配置
├── IDENTITY.md        # AI 身份配置
├── USER.md            # 用户配置
├── 01.jpg             # 群二维码
└── README.md          # 项目说明
```

## 🔧 使用方法

1. 打开 `config-editor.html`
2. 在对应的标签页中编辑配置（灵魂 / 身份 / 用户）
3. 实时预览生成的 Markdown 内容
4. 使用复制按钮将配置复制到剪贴板
5. 将配置保存到对应的 `.md` 文件中

## 🌐 龙虾技术交流群

<div align="center">
  <img src="01.jpg" alt="扫码加入交流群" width="200">
  <p>扫码加入龙虾技术兴趣交流群</p>
</div>

## 📝 技术栈

- **前端**: HTML5 + CSS3 + Vanilla JavaScript
- **设计风格**: 复古 Windows 95 风格
- **字体**: VT323 + Press Start 2P (Google Fonts)

## 🚀 初始化配置

首次使用时需要填写以下内容：

### SOUL.md
- 核心信念：你的 AI 坚持的基本原则
- 边界：哪些事情绝不会做
- 风格：整体感觉和氛围
- 连续性：关于会话记忆的说明

### IDENTITY.md
- 名称：AI 的名字
- 类型：AI/机器人/其他
- 风格：敏锐/温暖/混乱/平静
- 表情符号：标志性签名（推荐 🦞）
- 头像：可选的头像图片

### USER.md
- 用户姓名和称呼
- 时区和所在地
- 语言偏好
- 沟通风格偏好
- 当前关注的项目

## 📄 License

MIT License

---

做你凌晨2点真正想谈的助理。不是企业的无人机。不是马屁精。只是......很好。
