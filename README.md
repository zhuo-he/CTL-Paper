# paper list
## Continual Domain Adaptation
- [ICCV 2021] Generalized source-free domain adaptation [[arxiv](https://arxiv.org/abs/2108.01614)]

- [AAAI 2021] Gradient Regularized Contrastive Learning for Continual Domain Adaptation [[arxiv](https://arxiv.org/abs/2103.12294v1)]

- [CVPR 2022] On Generalizing Beyond Domains in Cross-Domain Continual Learning [[arxiv](https://arxiv.org/abs/2203.03970)]

## Continual Domain Shift Learning
- [ICLR 2023] DEJA VU: Continual Model Generalization For Unseen Domains [[arxiv](https://arxiv.org/abs/2301.10418)]

  - 提出CDSL setting，并通过data augmentation、pseudo label refine和prototype learning来确保TDA、TDG和FA任务的性能
 
- [ICCV 2023] Complementary Domain Adaptation and Generalization for Unsupervised Continual Domain Shift Learning [[arxiv](https://arxiv.org/abs/2303.15833)]

  - CDSL setting下，DA与DG方法相互配合，DA为DG提供准确的pseudo label，DG为DA提供更好的初始化模型参数
 
- [CVPR 2021] Adaptive Methods for Real-World Domain Generalization [[arxiv](https://arxiv.org/abs/2103.15796)]

  - DG只是保证模型在unseen domain整体表现良好，而对于一个具体的domain，由于"adaptive gap"的存在而阻碍了泛化性能的提升 

- [SIGKDD 2023] Domain-Specific Risk Minimization for Domain Generalization [[arxiv](https://arxiv.org/abs/2208.08661)]

  - 为解决DG的"adaptive gap"问题，推导了一个包含"adaptive gap"的泛化误差上界，从而启发出"test-time model selection"与"test-time retraining"方法

## Temporal/Envolving Domain Generalization
- [NeurIPS 2022] Wild-Time: A Benchmark of in-the-Wild Distribution Shift over Time [[arxiv](https://arxiv.org/abs/2211.14238)]

- [ECCV 2020] Sequential Learning for Domain Generalization [[arxiv](https://arxiv.org/abs/2004.01377)]

- [NeurIPS 2021] Training for the Future: Interpolation Loss to Generalize Along Time [[arxiv](https://arxiv.org/abs/2108.06721v1)]

- [AAAI 2023] Foresee What You Will Learn Data Augmentation for Domain Generalization in Non-Stationary Environments [[arxiv](https://arxiv.org/abs/2301.07845)]

- [ICLR 2023] Temporal Domain Generalization with Drift-Aware Dynamic Neural Network [[arxiv](https://arxiv.org/abs/2205.10664)]

- [arXiv 2023] CODA: Temporal Domain Generalization via Concept Drift Simulator [[arxiv](https://arxiv.org/abs/2310.01508)]

  - 不同于绝大多数model centric方法，这篇文章提出了一种data centric的方法，通过OOD generation来模拟未来数据，具体通过correlation predictor与data simulator来完成

- [arXiv 2023] Prompting-based Efficient Temporal Domain Generalization [[arxiv](https://arxiv.org/abs/2310.02473v1)]

  - 基于prompt的temporal DG方法，specific prompt用来捕捉每个特定domain的信息，temporal prompt用于捕捉时序信息以预测未来domain的信息，global prompt用来捕捉cross domain general的信息 

- Adaptive Invariant Representation Learning for Non-stationary Domain Generalization [[pdf](https://openreview.net/attachment?id=jnZtTUdWyi&name=pdf)]

- Time-sensitive Weight Averaging for Practical Temporal Domain Generalization [[pdf](https://openreview.net/pdf?id=CSm099mlOL)]
  
  - 一种对时间敏感的权重平均(weight average)方法，对每个时间步的K个model snapshots进行ensemble，并在更加现实的benchmark上进行性能评估


## Continual Domain Generalization with Temporal Drift
- [NeurIPS 2023] Evolving Standardization for Continual Domain Generalization over Temporal Drift

## Causal Structure Learning
- [ICCV 2023] iDAG: Invariant DAG Searching for Domain Generalization [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Huang_iDAG_Invariant_DAG_Searching_for_Domain_Generalization_ICCV_2023_paper.html)]

- [CVPR 2021] CausalVAE: Structured Causal Disentanglement in Variational Autoencoder [[arxiv](https://arxiv.org/abs/2004.08697)]

- [ICLR 2022] Learning Temporally Causal Latent Processes from General Temporal Data [[arxiv](https://arxiv.org/abs/2110.05428)]

- [NeurIPS 2022] Temporally Disentangled Representation Learning [[arxiv](https://arxiv.org/abs/2210.13647)]
