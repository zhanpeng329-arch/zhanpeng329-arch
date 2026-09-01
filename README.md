<div align="center">

# 你好，我是 Zipper 👋

**AI Agent 方向 · 全栈工程师**&nbsp;·&nbsp;中国传媒大学&nbsp;·&nbsp;北京

> Striving for impact. Still learning, still growing.

独立完成并上线 **4 款科研 AI 产品**：<br/>
**[Yila AI](https://yila.ai)** · **[FigPad](https://figpad.ai)** · **[Citely](https://citely.ai)** · **[Literfy](https://literfy.ai)**<br/>
主攻 Agent 长任务、工具调用、人机协同与成本可控的商业化闭环。

<a href="https://yila.ai"><img src="https://img.shields.io/badge/主力产品-yila.ai-0A66C2?style=for-the-badge" alt="yila.ai"/></a>
<a href="mailto:zipp@yila.ai"><img src="https://img.shields.io/badge/邮箱-zipp%40yila.ai-EA4335?style=for-the-badge&logo=maildotru&logoColor=white" alt="email"/></a>
<img src="https://komarev.com/ghpvc/?username=zhanpeng329-arch&style=for-the-badge&color=6f42c1&label=%E4%B8%BB%E9%A1%B5%E8%AE%BF%E5%AE%A2" alt="views"/>

</div>

---

## 🐍 看小蛇吃掉我的提交格子

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zhanpeng329-arch/zhanpeng329-arch/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/zhanpeng329-arch/zhanpeng329-arch/output/github-snake.svg" />
  <img alt="贡献图贪吃蛇动画" src="https://raw.githubusercontent.com/zhanpeng329-arch/zhanpeng329-arch/output/github-snake.svg" />
</picture>

</div>

## 📦 立体贡献图

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile-3d-contrib/profile-night-view.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./profile-3d-contrib/profile-green-animate.svg" />
  <img alt="3D 贡献图" src="./profile-3d-contrib/profile-green-animate.svg" />
</picture>

<sub>提交量 / Issue / PR / Review / 仓库数雷达图，每日自动更新</sub>

</div>

---

## 🧑‍💻 关于我

- 🤖 主要做 **大模型 Agent 系统**，也一个人把它们做成能收费的产品：任务规划、工具调用、人机协同确认、长任务的暂停与恢复、以及用量与成本的可控计量。
- 🧱 我同样在意「上线之后」的那一半工作——发布流程、异常与恢复、以及**可复现、可复算的验证证据**，而不只是一个能跑的 Demo。
- 🔬 产品都长在**科研场景**里：论文检索、文献综述、引用核验、科研图与学术海报。
- 🎓 就读于 **中国传媒大学**，研究方向为 AI Agent 产品与应用。常驻北京。
- 📫 想聊聊具体细节，欢迎来信：**zipp@yila.ai**

<details>
<summary><b>English version (click to expand)</b></summary>

<br/>

I'm an **AI-agent-focused full-stack engineer**, studying at Communication University of China, based in Beijing.

I've independently built and shipped **four AI products for the research community** — Yila AI,
FigPad, Citely and Literfy — covering paper discovery, literature reviews, citation verification
and scientific figures. My work centres on long-running agent tasks: planning, tool calling,
human-in-the-loop approval, pause & resume, and keeping usage and cost measurable.

I care as much about the unglamorous half of shipping — release process, failure recovery and
re-runnable evidence — as I do about the demo.

Happy to go into detail over email: **zipp@yila.ai**

</details>

---

## 🚀 正在做的产品

> 4 款已上线的科研 AI 产品，从产品设计、研发到增长与商业化基本由我独立完成。

<br/>

### 🧪 Yila AI — 持久化科研 Agent 工作台 &nbsp;<sub>⭐ 主力项目</sub>

<a href="https://yila.ai"><b>yila.ai</b></a> &nbsp;·&nbsp; 2026.06 至今

**在做一件什么事**

把「论文发现 → 文献综述 → 引用核验 → 科研图 / 学术海报」这些散落的单点能力，
组织成可复用的 **Research Agents / Playbooks**：一次研究任务可以连续跑几十分钟，
中途能暂停、能恢复、能追问，最终以 **Artifact（可下载的产物）** 交付，
而不是留下一段聊天记录。可以理解为「学术版 Manus」。

**工程上真正难的地方**

| 挑战 | 我的解法 |
| :--- | :--- |
| 长任务不能因为刷新、断网、发版就丢 | 服务端持久化会话与可重放的任务状态；转录由服务端投影，用户关掉浏览器任务照跑不误 |
| Agent 会执行花钱 / 不可逆的动作 | **人机协同确认门**：高成本或不可逆的操作先申请授权，用户拒绝则保证零副作用 |
| 要执行模型生成的不可信代码 | **默认拒绝出网的沙箱**，不向沙箱下发任何密钥；外部内容只能经受控通道落盘 |
| Token 成本必须算得清 | **预扣 → 真实用量计量 → 结算入账**，失败或中断自动释放，全链路可审计 |
| Agent 行为不能靠「感觉」验收 | 成体系的 Agent 评测集与可复跑的发布门禁；发布走围栏与零残留排空 |
| 模型会挂、上下文会爆 | 多模型自动降级链路 + 长上下文压缩，长会话不中断 |

**沉淀**：把研究方法固化成可复用的技能与工具集，让复杂长任务可计量、可控成本，具备规模化收费的基础。

<br/>

---

<br/>

### 其余三款已上线产品

<table>
<tr>
<td width="33%" valign="top">

#### 🎨 FigPad
<a href="https://figpad.ai"><b>figpad.ai</b></a><br/>
<sub>AI 科研图与可编辑视觉工作台</sub>

生成科研配图后**不是给你一张死图**：Make Editable 之后每个标签都能改，可导出 SVG / PPTX。

以云端归档、父子版本与失败重试支撑长期交付，围绕「注册 → 生成 → 编辑 → 导出 → 付费」漏斗持续迭代。

</td>
<td width="33%" valign="top">

#### 🔍 Citely
<a href="https://citely.ai"><b>citely.ai</b></a><br/>
<sub>AI 文献溯源与引用核查</sub>

专治大模型编造的参考文献：文本与参考文献经语义检索和多源交叉核验，输出 Verified / Mismatch / Not Found 与可信替代。

自建中英日韩黄金评测集，按类别与语种输出混淆矩阵驱动回归。已上线 Web、任务 API 与插件形态。

</td>
<td width="33%" valign="top">

#### 📚 Literfy
<a href="https://literfy.ai"><b>literfy.ai</b></a><br/>
<sub>AI 论文检索与文献综述</sub>

完整链路「研究主题 → Query 生成 → 多源检索 → 百篇级筛选 → 大纲编辑 → 综述生成 → 导出」。

以引用预分配、并行生成、心跳进度与失败恢复，保障长任务不会跑到一半烂尾。

</td>
</tr>
</table>

<br/>

### 🧩 开源小项目

**[obsidian-CodeIndentation](https://github.com/zhanpeng329-arch/obsidian-CodeIndentation)** — 修复 Obsidian 编辑器内代码块缩进行为的插件，已有社区用户在使用。

---

<div align="center">
<sub>感谢来访 —— 欢迎提 issue 或直接来信交流 🙌</sub>
</div>
