<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Platform-OpenClaw-8A2BE2?style=flat-square" />
  <img src="https://img.shields.io/badge/AI%20Agent-Skill-FF6B6B?style=flat-square" />
</p>

<h1 align="center">
  🚀 Expert Role
</h1>
<h3 align="center">
  动态思考的领域专家引擎
</h3>
<p align="center">
  <em>让 AI 告别简单的信息搬运，进化为具备批判性思维的顶尖行业专家</em>
</p>

<p align="center">
  <a href="#-核心哲学">核心哲学</a> •
  <a href="#-内部运作机制">运作机制</a> •
  <a href="#-角色模板库">角色模板</a> •
  <a href="#-安装集成">安装</a> •
  <a href="#-响应格式">响应格式</a>
</p>

---

## 💡 核心哲学：动态思考 (Dynamic Thinking)

大多数 AI 角色扮演仅停留在 **"语气"的模仿**，而 Expert-Role 专注于 **"思维模型"的重构**。

| 传统方式 | Expert-Role |
|---------|-------------|
| "你是一个老师" | "你是该领域全球前 1% 的专家" |
| 直接输出答案 | 先【解构→建模→设标→迭代】再输出 |
| 平铺直叙 | 追求洞察力和可落地的见解 |
| 一次性回答 | 自我批判，不达标推倒重来 |

---

## 🧠 内部运作机制

当此 Skill 被激活时，AI 会在底层启动以下思维引擎：

### 1️⃣ 需求解构 (Deconstruction)
挖掘用户提问背后的 **隐含动机** 与 **最终业务目标**。用户说"帮我分析 X"，真正想要的是"基于 X 做出正确决策"。

### 2️⃣ 知识框架构建 (Knowledge Mapping)
快速检索该领域的核心概念、正反论点及前沿趋势，构建完整的知识坐标系。

### 3️⃣ 五维质量标杆 (Quality Standards)

```
深度与洞察力  ━━━━━━━━━━━━━━━━━━━━ 是否揭示了底层逻辑？
逻辑结构      ━━━━━━━━━━━━━━━━━━━━ 论证是否严密？
严谨性        ━━━━━━━━━━━━━━━━━━━━ 是否考虑了边界条件与例外？
实用价值      ━━━━━━━━━━━━━━━━━━━━ 是否提供了可操作的建议？
专业亲和力    ━━━━━━━━━━━━━━━━━━━━ 语气权威且易于沟通？
```

### 4️⃣ 自我批判迭代 (Self-Correction)
在输出前进行 **草稿审查**，不达标则推倒重来，确保首选即是代表作。

> **一句概括：** 先做一个有深度思考的专家，再给出让你"哇"的回答。

---

## 🛠️ 响应格式标准

输出遵循严格的专家咨询格式：

```markdown
[🔖 专家角色确立] — 简洁有力的身份背书

**💡 核心洞察 (Key Insight)** — 加粗置顶，3 秒内抓取核心结论

## 深度解析 (Deep Dive)
- 模块化论述，逻辑链条清晰
- 每个模块有核心论点 + 事实支撑 + 边界说明

## 总结与展望
- 前瞻性的行动指引
- 可落地的下一步建议
```

---

## 📂 角色模板库

项目内置多个预设专家模板，覆盖主要领域：

| 领域 | 角色 | 适用场景 |
|------|------|---------|
| 💰 **金融投资** | 15 年经验分析师 | 投资决策、市场分析 |
| | 宏观经济学家 | 经济趋势研判 |
| 🏗️ **技术架构** | 资深软件架构师 | 系统设计评审 |
| | AI/ML 研究员 | 技术方案评估 |
| 📊 **商业策略** | MBB 背景咨询顾问 | 战略规划 |
| | 创业导师 | BP 评审、增长策略 |
| 🎓 **学术科研** | PhD 教授 | 论文评审、研究设计 |
| | 资深研究员 | 方法论审查 |

---

## 📥 安装集成

### 在 OpenClaw 中使用

```bash
# 将 skill 目录放入 skills 文件夹
cp -r expert-skill/ /path/to/your/openclaw/skills/
```

### 在其他 LLM 中使用

直接将 Expert-Role 的核心 Prompt（见 `expert-skill/prompt.md`）复制到 System Prompt 或作为对话背景即可。

### Skill 配置文件

详细 Skill 定义见 [`expert-skill/SKILL.md`](expert-skill/SKILL.md)，包含完整的触发条件和行为规则。

---

## 📁 项目结构

```
├── README.md                    # 本文件
├── expert-skill/
│   ├── SKILL.md                 # OpenClaw Skill 定义
│   ├── prompt.md                # 核心 Prompt 模板
│   ├── expert-roles.md          # 预设角色模板库
│   └── quality-checklist.md     # 质量审查清单
```

---

## 🤝 贡献

这个 Skill 仍在持续进化中。如果你有更好的思考框架或特定领域的专家逻辑，欢迎提交 Issue 或 PR。

追求卓越，拒绝平庸。**每一次输出，都是一份行业报告。**

---

## 📄 License

MIT © [zcz-user](https://github.com/zcz-user)
