# Anthropic 官方发布：Claude Opus/Sonnet 4.5 提示词指南

## 10 个让你效率翻倍的最佳实践

> 来源：[@minchoi](https://x.com/minchoi/status/1999874571806355477) Twitter 帖子整理
> 
> 基于 Anthropic 官方 Prompt Guide

---

## 1. 尽可能具体明确

**核心要点**：明确说出你想要什么（格式、语气、长度、目标受众）。Claude 4 会严格按照指令执行。

Claude 4.x 模型对清晰、明确的指令响应非常好。具体说明你期望的输出可以显著提升结果质量。

![示例图片](https://pbs.twimg.com/media/G8D6INRX0AIK-lo?format=jpg&name=medium)

---

## 2. 告诉它为什么需要

**核心要点**：一句话说明原因（例如："这是给高管看的" / "这必须符合法律要求" / "这要放进演示文稿"）能快速提升输出质量。

为你的指令提供背景或动机——比如解释为什么这个行为很重要——可以帮助 Claude 4.x 模型更好地理解你的目标，从而提供更有针对性的回应。

![示例图片](https://pbs.twimg.com/media/G8D6JxyXsAM7bG4?format=jpg&name=medium)

---

## 3. 你的示例就是真理

**核心要点**：如果你给出一个示例，Claude 会照着复制。糟糕的示例 = 糟糕的输出。

Claude 4.x 等现代模型会非常仔细地关注示例中的细节。确保你的示例与你想要鼓励的行为一致，并尽量减少任何你想避免的模式。

![示例图片](https://pbs.twimg.com/media/G8D6NxBaoAA--oO?format=jpg&name=medium)

---

## 4. 大项目？分小步检查点推进

**核心要点**：当你强制要求"逐步推进"而不是"一次性完成所有事"时，Claude 4.5 在长任务上表现更强。

Claude 4.5 模型在长时间推理任务上表现出色，具有卓越的状态跟踪能力。它通过专注于增量进步来保持方向感——一次稳步推进几件事，而不是试图一次完成所有事情。

![示例图片](https://pbs.twimg.com/media/G8D6QcFXQAE8NG4?format=jpg&name=medium)

---

## 5. 如果使用 Agent 工作流，请明确说明

**核心要点**：告诉它上下文是否会被压缩/保存到文件，以及在窗口刷新前保存状态。

如果你在一个会压缩上下文或允许将上下文保存到外部文件的 agent 框架中使用 Claude（比如 Claude Code），建议在提示中添加这些信息，以便 Claude 能够相应地调整行为。

![示例图片](https://pbs.twimg.com/media/G8D6T7BWUAE_MuM?format=jpg&name=medium)

---

## 6. 想要行动而非建议？说"去做"

**核心要点**：如果你问"建议修改"，它可能只会建议。如果你想要实际的编辑/实现，要明确请求这种行为。

Claude 4.5 模型被训练为精确遵循指令，并且从明确指示使用特定工具中受益。如果你希望 Claude 在工作时提供更新，可以明确要求它这样做。

![示例图片](https://pbs.twimg.com/media/G8D6WmdXAAQ-mKg?format=jpg&name=medium)

---

## 7. 通过说明"要做什么"来控制格式

**核心要点**：不要说"不要用 markdown"，而是说"写3个简短段落"或"返回 JSON"。

正向指令比负向指令更有效。告诉模型你想要什么格式，而不是你不想要什么。

![示例图片](https://pbs.twimg.com/media/G8D6hHOWwAIwhjF?format=jpg&name=medium)

---

## 8. 使用简单的"标签"（XML 标签）来引导行为

**核心要点**：官方推荐使用轻量级标签来设置默认行为，比如"主动型"vs"谨慎型"。

XML 标签可以帮助你组织提示的不同部分，让 Claude 更容易理解和遵循你的指令结构。

![示例图片](https://pbs.twimg.com/media/G8D6iGjX0AARWL9?format=jpg&name=medium)

---

## 9. 工具使用：不要在系统提示中"大喊"

**核心要点**：如果你的提示大喊"必须"，Claude Opus 4.5 可能会过度触发工具。使用更平和的引导方式。

Claude 4.5 模型倾向于效率，可能会在工具调用后跳过口头总结，直接进入下一个操作。虽然这创造了流畅的工作流程，但你可能更喜欢对其推理过程有更多可见性。用平静的语气引导，而不是强制性的语言。

![示例图片](https://pbs.twimg.com/media/G8D6juuXIAEl8Er?format=jpg&name=medium)

---

## 10. 如果关闭了"思考"功能，避免使用"思考"这个词

**核心要点**：Opus 4.5 对"think"这个词出奇地敏感——改用"consider / evaluate"（考虑/评估）代替。

当扩展思考功能被禁用时，Claude Opus 4.5 对"think"这个词及其变体特别敏感。使用替代词汇可以获得更好的结果。

![示例图片](https://pbs.twimg.com/media/G8D6m39XUAECLR3?format=jpg&name=medium)

---

## 总结

这 10 条最佳实践的核心原则：

| 序号 | 要点 | 关键词 |
|:---:|:---|:---|
| 1 | 具体明确 | 格式、语气、长度 |
| 2 | 说明原因 | 背景、动机 |
| 3 | 示例即真理 | 高质量示例 |
| 4 | 分步推进 | 增量进步 |
| 5 | 说明 Agent 环境 | 上下文管理 |
| 6 | 明确要求行动 | "去做"而非"建议" |
| 7 | 正向格式指令 | 说"要什么"而非"不要什么" |
| 8 | XML 标签引导 | 结构化提示 |
| 9 | 温和引导工具 | 避免强制性语言 |
| 10 | 避免"think" | 用 consider/evaluate 替代 |

---

## 延伸阅读

- [Anthropic 官方 Claude 4 最佳实践文档](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/claude-4-best-practices)
- [Claude Code 最佳实践](https://www.anthropic.com/engineering/claude-code-best-practices)
- [提示词工程综合指南](https://claude.com/blog/best-practices-for-prompt-engineering)

---

*整理自 @minchoi 的 Twitter 帖子，原文发布于 2024年12月14日*
