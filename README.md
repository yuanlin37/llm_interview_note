# LLMs 相关知识及面试题


## 简介

本仓库为大模型面试相关概念，由本人参考网络资源整理，欢迎阅读，如果对你有用，麻烦点一下 `🌟 star`，谢谢！

为了在低资源情况下，学习大模型，进行动手实践，创建 [tiny-llm-zh](https://github.com/wdndev/tiny-llm-zh)仓库，旨在构建一个小参数量的中文大语言模型，该项目已部署，可以在如下网站上体验：[ModeScope Tiny LLM](https://www.modelscope.cn/studios/wdndev/tiny_llm_92m_demo/summary)。


其他学习资源推荐：

- [llama3-from-scratch-zh](https://github.com/wdndev/llama3-from-scratch-zh) : 从零实现 llama3, 可加载 meta 官方权重，可在本地笔记本（16G内存）调试运行
- [tiny-rag](https://github.com/wdndev/tiny-rag) : 实现一个简单的RAG系统，支持多路召回、重排等功能，快速了解搜索相关内容；
- [AI 工程师八股](https://github.com/wdndev/ai_interview_note) : 包含深度学习、机器学习、推荐系统、搜索系统等通用知识



## 在线阅读

在线阅读链接：[LLMs Interview Note](http://yuanlin37.github.io/llm_interview_note)


## 注意：

相关答案为自己撰写，若有不合理地方，请指出修正，谢谢！

欢迎关注微信公众号，会不定期更新LLM内容，以及一些面试经验：

 <img src=https://github.com/wdndev/personal/blob/main/image/llmers_weixin.jpg width = "427" height = "156" alt="weixin" />


## 目录

* [首页](/)
* [真实面试题](/ch1)
* [01.大语言模型基础](/01.大语言模型基础/)
  * [1.1 大模型发展历程](/01.大语言模型基础/)
    * [1.语言模型](/01.大语言模型基础/1.语言模型/1.语言模型.md "1.语言模型")
  * [1.2 分词与词向量](/01.大语言模型基础)
    * [1.分词](/01.大语言模型基础/1.分词/1.分词.md)
    * [2.jieba分词用法及原理](/01.大语言模型基础/2.jieba分词用法及原理/2.jieba分词用法及原理.md)
    * [3.词性标注](/01.大语言模型基础/3.词性标注/3.词性标注.md)
    * [4.句法分析](/01.大语言模型基础/4.句法分析/4.句法分析.md "4.句法分析")
    * [5.词向量](/01.大语言模型基础/5.词向量/5.词向量.md "5.词向量")
  * [1.3 语言模型基础知识](/01.大语言模型基础/)
    * [Word2Vec](/01.大语言模型基础/Word2Vec/Word2Vec.md "Word2Vec")
    * [NLP三大特征抽取器（CNN/RNN/TF）](/01.大语言模型基础/NLP三大特征抽取器（CNN-RNN-TF）/NLP三大特征抽取器（CNN-RNN-TF）.md)
    * [NLP面试题](/01.大语言模型基础/NLP面试题/NLP面试题.md "NLP面试题")
    * [LLM为什么Decoder only架构](</01.大语言模型基础/LLM为什么Decoder only架构/LLM为什么Decoder only架构.md> "LLM为什么Decoder only架构")
  * [1.4 深度学习](/01.大语言模型基础/)
    * [1.激活函数](/01.大语言模型基础/1.激活函数/1.激活函数.md)
  * [1.5 一些题目](/01.大语言模型基础/)
    * [1.llm概念](/01.大语言模型基础/1.llm概念/1.llm概念.md)
* [02.大语言模型架构](/02.大语言模型架构/)
  * [2.1 Transformer模型](/02.大语言模型架构/)
    * [1.attention](/02.大语言模型架构/1.attention/1.attention.md "1.attention")
    * [2.layer\_normalization](/02.大语言模型架构/2.layer_normalization/2.layer_normalization.md "2.layer_normalization")
    * [3.位置编码](/02.大语言模型架构/3.位置编码/3.位置编码.md "3.位置编码")
    * [4.tokenize分词](/02.大语言模型架构/4.tokenize分词/4.tokenize分词.md "4.tokenize分词")
    * [5.token及模型参数](/02.大语言模型架构/5.token及模型参数/5.token及模型参数.md "5.token及模型参数")
    * [6.激活函数](/02.大语言模型架构/6.激活函数/6.激活函数.md "6.激活函数")
  * [2.2 注意力](/02.大语言模型架构/)
    * [MHA\_MQA\_GQA](/02.大语言模型架构/MHA_MQA_GQA/MHA_MQA_GQA.md "MHA_MQA_GQA")
  * [2.3 解码部分](/02.大语言模型架构/)
    * [解码策略（Top-k & Top-p & Temperature）](</02.大语言模型架构/解码策略（Top-k & Top-p & Temperatu/解码策略（Top-k & Top-p & Temperature）.md> "解码策略（Top-k & Top-p & Temperature）")
  * [2.4 BERT](/02.大语言模型架构/)
    * [bert细节](/02.大语言模型架构/bert细节/bert细节.md "bert细节")
    * [Transformer架构细节](/02.大语言模型架构/Transformer架构细节/Transformer架构细节.md "Transformer架构细节")
    * [bert变种](/02.大语言模型架构/bert变种/bert变种.md "bert变种")
  * [2.5 常见大模型](/02.大语言模型架构/)
    * [llama系列模型](/02.大语言模型架构/llama系列模型/llama系列模型.md "llama系列模型")
    * [chatglm系列模型](/02.大语言模型架构/chatglm系列模型/chatglm系列模型.md "chatglm系列模型")
    * [llama 2代码详解](</02.大语言模型架构/llama 2代码详解/llama 2代码详解.md> "llama 2代码详解")
    * [llama 3](</02.大语言模型架构/llama 3/llama 3.md> "llama 3")
  * [2.6 MoE](/02.大语言模型架构/)
    * [1.MoE论文](/02.大语言模型架构/1.MoE论文/1.MoE论文.md "1.MoE论文")
    * [2.MoE经典论文简牍](/02.大语言模型架构/2.MoE经典论文简牍/2.MoE经典论文简牍.md "2.MoE经典论文简牍")
    * [3.LLM MoE ：Switch Transformers](</02.大语言模型架构/3.LLM MoE ：Switch Transformers/3.LLM MoE ：Switch Transformers.md> "3.LLM MoE ：Switch Transformers")
* [03.训练数据集](/03.训练数据集/)
  * [3.1 数据集](/03.训练数据集/)
    * [数据格式](/03.训练数据集/数据格式/数据格式.md "数据格式")
  * [3.2 模型参数](/03.训练数据集/)
* [04.分布式训练](/04.分布式训练/)
  * [4.1 基础知识](/04.分布式训练/)
    * [1.概述](/04.分布式训练/1.概述/1.概述.md "1.概述")
    * [2.数据并行](/04.分布式训练/2.数据并行/2.数据并行.md "2.数据并行")
    * [3.流水线并行](/04.分布式训练/3.流水线并行/3.流水线并行.md "3.流水线并行")
    * [4.张量并行](/04.分布式训练/4.张量并行/4.张量并行.md "4.张量并行")
    * [5.序列并行](/04.分布式训练/5.序列并行/5.序列并行.md "5.序列并行")
    * [6.多维度混合并行](/04.分布式训练/6.多维度混合并行/6.多维度混合并行.md "6.多维度混合并行")
    * [7.自动并行](/04.分布式训练/7.自动并行/7.自动并行.md "7.自动并行")
    * [8.moe并行](/04.分布式训练/8.moe并行/8.moe并行.md "8.moe并行")
    * [9.总结](/04.分布式训练/9.总结/9.总结.md "9.总结")
  * [4.2 DeepSpeed](/04.分布式训练/)
    * [deepspeed介绍](/04.分布式训练/deepspeed介绍/deepspeed介绍.md "deepspeed介绍")
  * [4.3 Megatron](/04.分布式训练/)
  * [4.4 训练加速](/04.分布式训练/)
  * [4.5 一些有用的文章](/04.分布式训练/)
  * [4.6 一些题目](/04.分布式训练/)
    * [1.分布式训练题目](/04.分布式训练/分布式训练题目/分布式训练题目.md "分布式训练题目")
    * [2.显存问题](/04.分布式训练/1.显存问题/1.显存问题.md "1.显存问题")
* [05.有监督微调](/05.有监督微调/)
  * [5.1 理论](/05.有监督微调/)
    * [1.基本概念](/05.有监督微调/1.基本概念/1.基本概念.md "1.基本概念")
    * [2.prompting](/05.有监督微调/2.prompting/2.prompting.md "2.prompting")
    * [3.adapter-tuning](/05.有监督微调/3.adapter-tuning/3.adapter-tuning.md "3.adapter-tuning")
    * [4.lora](/05.有监督微调/4.lora/4.lora.md "4.lora")
    * [5.总结](/05.有监督微调/5.总结/5.总结.md "5.总结")
  * [5.2 微调实战](/05.有监督微调/)
    * [llama2微调](/05.有监督微调/llama2微调/llama2微调.md "llama2微调")
    * [ChatGLM3微调](/05.有监督微调/ChatGLM3微调/ChatGLM3微调.md "ChatGLM3微调")
  * [5.3 一些题目](/05.有监督微调/)
    * [1.微调](/05.有监督微调/1.微调/1.微调.md "1.微调")
    * [2.预训练](/05.有监督微调/2.预训练/2.预训练.md "2.预训练")
* [06.推理](/06.推理/)
  * [6.1 推理框架](/06.推理/)
    * [0.llm推理框架简单总结](/06.推理/0.llm推理框架简单总结/0.llm推理框架简单总结.md "0.llm推理框架简单总结")
    * [1.vllm](/06.推理/1.vllm/1.vllm.md "1.vllm")
    * [2.text_generation\_inference](/06.推理/2.text_generation_inference/2.text_generation_inference.md "2.text_generation_inference")
    * [3.faster_transformer](/06.推理/3.faster_transformer/3.faster_transformer.md "3.faster_transformer")
    * [4.trt_llm](/06.推理/4.trt_llm/4.trt_llm.md "4.trt_llm")
  * [6.2 推理优化技术](/06.推理/)
    * [llm推理优化技术](/06.推理/llm推理优化技术/llm推理优化技术.md "llm推理优化技术")
  * [6.3 量化](/06.推理/)
  * [6.4 vLLM](/06.推理/)
  * [6.5 一些题目](/06.推理/)
    * [1.推理](/06.推理/1.推理/1.推理.md "1.推理")
* [07.强化学习](/07.强化学习)
  * [7.1 强化学习原理](/07.强化学习)
    * [策略梯度（pg）](/07.强化学习/策略梯度（pg）/策略梯度（pg）.md "策略梯度（pg）")
    * [近端策略优化(ppo)](/07.强化学习/近端策略优化(ppo)/近端策略优化(ppo).md "近端策略优化(ppo)")
  * [7.2 RLHF](/07.强化学习)
    * [大模型RLHF：PPO原理与源码解读](/07.强化学习/大模型RLHF：PPO原理与源码解读/大模型RLHF：PPO原理与源码解读.md "大模型RLHF：PPO原理与源码解读")
    * [DPO](/07.强化学习/DPO/DPO.md "DPO")
  * [7.3 一些题目](/07.强化学习)
    * [1.rlhf相关](/07.强化学习/1.rlhf相关/1.rlhf相关.md "1.rlhf相关")
    * [2.强化学习](/07.强化学习/2.强化学习/2.强化学习.md "2.强化学习")
* [08.检索增强RAG](/08.检索增强rag/)
  * [8.1 RAG](/08.检索增强rag/)
    * [检索增强llm](/08.检索增强rag/检索增强llm/检索增强llm.md "检索增强llm")
    * [rag（检索增强生成）技术](/08.检索增强rag/rag（检索增强生成）技术/rag（检索增强生成）技术.md "rag（检索增强生成）技术")
  * [8.2 Agent](/08.检索增强rag/)
    * [大模型agent技术](/08.检索增强rag/大模型agent技术/大模型agent技术.md "大模型agent技术")
* [09.大语言模型评估](/09.大语言模型评估/)
  * [9.1 模型评估](/09.大语言模型评估/)
    * [1.评测](/09.大语言模型评估/1.评测/1.评测.md "1.评测")
  * [9.2 LLM幻觉](/09.大语言模型评估/)
    * [1.大模型幻觉](/09.大语言模型评估/1.大模型幻觉/1.大模型幻觉.md "1.大模型幻觉")
    * [2.幻觉来源与缓解](/09.大语言模型评估/2.幻觉来源与缓解/2.幻觉来源与缓解.md "2.幻觉来源与缓解")
* [10.大语言模型应用](/10.大语言模型应用/)
  * [10.1 思维链提示](/10.大语言模型应用/)
    * [1.思维链（cot）](/10.大语言模型应用/1.思维链（cot）/1.思维链（cot）.md "1.思维链（cot）")
  * [10.2 LangChain框架](/10.大语言模型应用/)
    * [1.langchain](/10.大语言模型应用/1.langchain/1.langchain.md "1.langchain")
* [98.相关课程](/98.相关课程/)
* [99.参考资料](/99.参考资料/)







