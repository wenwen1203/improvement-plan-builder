# Improvement Plan Builder / 学校改进计划制定助手

A QoderWork skill that guides teachers through systematically breaking down improvement goals into actionable plans with quality feedback at every step.

一款 QoderWork Skill，引导教师将改进目标系统拆解为可执行的改进计划，并在每一步提供质量反馈。

> **Quality over completeness.** One solid sub-goal with well-designed actions beats five vague ones. Better to do fewer things well than many things superficially.
>
> **质量优先于完整。** 一个扎实的子目标加配套行动，胜过五个空泛的子目标。宁可少做几个，也要确保每一个都能落地。

---

## What This Skill Does / 本 Skill 功能

When a teacher has identified an improvement goal (typically from evidence chain analysis), this skill:

当教师已确定改进目标（通常来自证据链分析）时，本 Skill 会：

1. **Confirms the Goal / 确认目标** — quick-checks the Goal against 5 quality dimensions (direction, anchoring, scope, measurability, challenge). 用 5 个质量维度快速检查目标。
2. **Decomposes sub-goals / 拆解子目标** — guides logical breakdown into 2-4 concrete, measurable sub-objectives. 引导逻辑拆解为 2-4 个具体可衡量的子目标。
3. **Designs actions per sub-goal / 逐个设计行动** — for each sub-goal, develops action strategies with timeline, resources, and responsibilities. 为每个子目标设计行动策略，含时间线、资源和责任人。
4. **Sets success criteria / 设定成功标准** — defines what "success looks like" with concrete indicators and review mechanisms. 用具体指标定义"成功长什么样"并设计复盘机制。
5. **Reviews overall quality / 整体质量检查** — checks the complete plan against quality standards before finalizing. 在定稿前对完整计划进行质量标准检查。

---

## Hybrid Coaching Approach / 混合式引导方法

This skill uses a **guide → feedback → continue** loop:

本 Skill 使用**引导 → 反馈 → 继续**的循环模式：

- **Guide**: Ask targeted questions for each sub-goal rather than generating everything at once. 逐步引导，而不是一次生成全部内容。
- **Feedback**: After each sub-goal is drafted, provide quality feedback using a 4-level rubric (initial → developing → effective → excellent). 每个子目标完成后，使用四级量规提供质量反馈。
- **Continue**: Teacher decides whether to revise or move on to the next sub-goal. 教师决定是修改还是继续下一个子目标。

---

## File Structure / 文件结构

```
improvement-plan-builder/
├── SKILL.md                  # Core skill: role, principles, 5-step flow, quality feedback protocol
├── planning-framework.md     # Reference: templates, quality standards, discussion prompts, rubrics
└── README.md                 # This file
```

---

## Quality Standards Rubric / 质量标准量规

The skill evaluates each sub-goal against four quality levels:

本 Skill 用四个质量等级评估每个子目标：

| Level | Description |
|-------|-------------|
| Initial (初步) | Goal stated but vague, actions listed without logic |
| Developing (发展中) | Goal clearer, actions somewhat connected to goal |
| Effective (有效) | Specific measurable goal, well-designed actions with timeline |
| Excellent (卓越) | Goal drives systemic change, actions mutually reinforcing with built-in feedback loops |

---

## Companion Skill / 配套 Skill

This skill picks up where the evidence chain coach leaves off. If you haven't yet identified your improvement goal through data-driven inquiry, start with:

本 Skill 承接证据链教练的输出。如果尚未通过数据驱动的探究确定改进目标，请先使用：

**[datawise-evidence-chain-coach](https://github.com/wenwen1203/datawise-evidence-chain-coach)** — DataWise Evidence Chain Coach / DataWise 证据链引导式思考教练

---

## License / 许可

MIT License — feel free to use, adapt, and share.

MIT 许可证 — 可自由使用、改编和分享。
