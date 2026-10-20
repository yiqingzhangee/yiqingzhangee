# 张屹綮 | Yiqing Zhang

**Risk Intelligence · Graph Mining · Multimodal AI Safety**

<p>
  <a href="https://yiqingzhangee.github.io/">个人网站</a> ·
  <a href="https://scholar.google.com/citations?user=GPcGmDQAAAAJ&amp;hl=en">Google Scholar</a> ·
  <a href="mailto:yiqingzhangee@gmail.com">Email</a>
</p>

---

## 关于我 | About

我是一名风险智能技术负责人，长期关注如何把图挖掘、机器学习和大模型能力转化为可持续运行的真实风控系统。

我的经历横跨复杂网络研究、支付反欺诈、电商营销风控和短视频内容安全。目前主要聚焦于多模态风险识别、LLM 驱动的审核与持续学习闭环、模型对抗鲁棒性，以及 VLM 推理优化。

> I build production risk-intelligence systems at the intersection of graph mining, multimodal learning, and AI safety.

## 关注方向 | Focus

- **图风控与团伙挖掘**：动态图、异质关系、目标社区搜索、半监督风险扩散
- **多模态风险识别**：文本、图像、视频与行为信号的联合建模
- **LLM/VLM 风控落地**：数据治理、审核辅助、轻量模型蒸馏与持续学习
- **模型安全与可靠性**：对抗评测、分层防御、误伤控制与回归评估
- **生产推理优化**：量化、KV cache、投机解码、视觉 token 压缩

## 工业经历 | Industry

### ByteDance / TikTok · Risk Intelligence

**2021.11 – 至今**

- 在 TikTok Shop 建设覆盖多个国家和市场的营销风险感知体系，融合设备、账号、地址、关系图和行为等信号，支持不同市场阶段的统一识别与差异化防控。
- 在 TikTok 短视频业务负责行为与内容风险治理，推动召回、模型、人审、黑库和线上策略形成可回流的闭环。
- 主导“LLM 数据清洗 + 轻量模型持续重训”链路，以大模型提升数据生产效率，以小模型承接高吞吐、低成本的在线判断。
- 建设多模态审核模型的对抗评测与分层防御能力，并推进 VLM 在显存、延迟、吞吐和视觉 token 成本上的端到端优化。

### Ant Group · Risk Graph Mining

**2018.01 – 2021.11**

- 负责支付与商家风险场景中的图挖掘和图深度学习，面向 20+ 风险场景识别隐蔽、协同的欺诈团伙。
- 将实时团伙发现建模为目标社区搜索，在虚假注册、企业认证等场景实现秒级风险社区发现。
- 推动半监督社区搜索与图深度学习方案落地，沉淀可复用的团伙识别方法与工程能力。

## 学术经历 | Research

- **香港浸会大学**，计算机科学系，博士后研究员，2016 – 2017
- **复旦大学**，电子工程，博士，2010 – 2016
- **复旦大学**，电子信息科学与技术，学士，2003 – 2007

研究起点是复杂网络、时序网络及其传播动力学。这段训练塑造了我处理工业风险问题的方式：从关系结构、动态演化和群体行为出发，而不只把风险识别视为独立样本分类。

## 代表论文 | Selected Publications

1. **eRiskCom: An E-commerce Risky Community Detection Platform**  
   F. Liu, Z. Li, B. Wang, J. Yang, J. Huang, **Y.-Q. Zhang**, et al.  
   *The VLDB Journal*, 31, 1085–1101, 2022.  
   [[Paper]](https://doi.org/10.1007/s00778-021-00723-z)

2. **Spectral Analysis of Epidemic Thresholds of Temporal Networks**  
   **Y.-Q. Zhang**, X. Li, A. V. Vasilakos.  
   *IEEE Transactions on Cybernetics*, 50(5), 1965–1977, 2020.  
   [[Paper]](https://ieeexplore.ieee.org/document/8031280)

3. **Human Interactive Patterns in Temporal Networks**  
   **Y.-Q. Zhang**, X. Li, J. Xu, A. V. Vasilakos.  
   *IEEE Transactions on Systems, Man, and Cybernetics: Systems*, 45(2), 214–222, 2015.  
   [[Paper]](https://doi.org/10.1109/TSMC.2014.2360505)

4. **Towards a Temporal Network Analysis of Interactive WiFi Users**  
   Y. Zhang, L. Wang, **Y.-Q. Zhang**, X. Li.  
   *EPL (Europhysics Letters)*, 98(6), 68002, 2012.  
   [[Paper]](https://arxiv.org/abs/1206.4781)

5. **Evolution of Scaling Emergence in Large-Scale Spatial Epidemic Spreading**  
   L. Wang, X. Li, **Y.-Q. Zhang**, Y. Zhang, K. Zhang.  
   *PLOS ONE*, 6(7), e21197, 2011.  
   [[Paper]](https://doi.org/10.1371/journal.pone.0021197)

完整论文列表见 [Google Scholar](https://scholar.google.com/citations?user=GPcGmDQAAAAJ&hl=en)。

## 技术栈 | Toolkit

| 领域 | 技术与方法 |
| --- | --- |
| Graph ML | Graph Mining, Community Search, GNN, Heterogeneous Graphs, Temporal Networks |
| LLM / VLM | PyTorch, Qwen/LLaMA, SFT, Distillation, Multimodal Evaluation |
| Model Serving | FP8, KV Cache, Speculative Decoding, Token Compression |
| Risk Systems | Anti-Fraud, Trust & Safety, Continual Learning, Human-in-the-Loop |
| Data & Infra | Spark, Hive, Distributed Training, Online/Offline Feature Pipelines |

## 当前关注 | Current Work

我正在持续探索三类问题：

1. 如何把关系结构和群体行为知识更有效地引入大模型风险推理；
2. 如何建立可解释、可回归、可持续迭代的多模态模型安全评测体系；
3. 如何让大模型负责高价值推理与数据生产，同时由轻量模型稳定承接在线流量。

欢迎围绕 **Graph ML、Anti-Fraud、Trust & Safety、Multimodal AI Safety** 交流。
