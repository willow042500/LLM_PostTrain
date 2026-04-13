# LLM Post-Training

本项目用于学习和实现大语言模型（LLM）后训练的核心技术，从底层原理出发，手动实现关键算法。

## 涵盖内容

- **SFT (Supervised Fine-Tuning)** — 监督微调，使用标注数据对预训练模型进行指令跟随能力的训练
- **LoRA (Low-Rank Adaptation)** — 低秩适配，通过低秩矩阵分解实现参数高效微调
- **GRPO (Group Relative Policy Optimization)** — 群组相对策略优化，一种用于对齐训练的强化学习算法

## 目标

- 理解各后训练方法的数学原理
- 从零实现核心训练逻辑
- 对比不同方法的效果与适用场景
