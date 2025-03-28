### 大型语言模型（LLMs）在网络安全中的应用研究笔记

## **WHEN LLMS MEET CYBERSECURITY: A SYSTEMATIC LITERATURE REVIEW**

**研究对象:**300 多篇文献,25 种 LLM 和 10 多个下游应用场景

**关键研究问题:**三个，面向网络安全的 LLM 构建、LLM 在各类网络安全任务中的应用、该领域面临的挑战与未来研究方向。

**目的:**旨在揭示 LLM 在增强网络安全实践中的巨大潜力，并为该领域应用 LLM 提供有价值的参考资源。

**提供的资源:**一个关于 LLM 在网络安全中应用的实用指南列表，详见https://github.com/tmylla/Awesome-LLM4Cybersecurity。

**研究对象:** ChatGPT [1]、Llama [2] 等先进模型及其衍生模型 [3, 4, 5] 为代表的大型语言模型（LLMs）

**关键词:**通用人工智能（AGI）

**前景提要:**网络安全快速演变，传统基于签名或规则的系统跟不上变化；人工智能进步快且优势明显

**三个关键问题:**

RQ1：如何构建面向网络安全领域的大型语言模型？

RQ2：大型语言模型在网络安全中有哪些潜在应用？ 

RQ3：大型语言模型在网络安全应用中面临哪些挑战，以及该领域的进一步研究方向是什么？ 

深入研究LLM适用的各种网络安全任务和应用场景，包括漏洞检测、安全代码生成、程序修复、二进制分析、IT 运营、威胁情报、异常检测以及大型语言模型辅助攻击，如表 1 所示。

#### 第三节：回答了RQ1：如何构建面向网络安全领域的大型语言模型？

从LLM原理和技术出发，提出构建领域模型的见解？这对于希望根据计算限制、私有数据和本地知识库等特定要求构建定制大语言模型的研究人员和从业者来说非常有价值

#### 第四节：回答了RQ2：大型语言模型在网络安全中有哪些潜在应用？ 

对LLM在十多项网络安全任务中的应用进行了广泛调查，任务包括威胁情报、漏洞检测、程序修复等。

#### 第五节：回答了RQ3：大型语言模型在网络安全应用中面临哪些挑战，以及该领域的进一步研究方向是什么？ 

挑战有：LLM的固有的漏洞和易受攻击性，尤其是LLM越狱攻击

#### 前情提要

大型语言模型主要可分为两类：开源模型和闭源模型。开源大型语言模型（如 Llama 和 Mixtral ）提供模型权重，研究人员可以针对特定的网络安全任务对模型进行微调。这种适应性在网络安全场景中尤为重要，例如处理私有数据以及根据定制需求微调模型。性能方面，开源大型语言模型在性能和规模上远逊于闭源大型语言模型。但闭源大型语言模型（通常称为商业大型语言模型，如 ChatGPT 和 Gemini）存在商业维护上的访问限制，缺乏透明度？可能存在偏差和局限

从网络安全行业日益增加的代码需求来说，基于代码的大型语言模型（如 CodeLlama 和 StarCoder）特别合适。与基于文本的LLM不同，基于代码的LLM是专门为理解和处理编程语言而设计的。它们能够执行的任务：代码补全、错误检测和自动代码审查。

LLMs在网络安全中的应用范围很广，包括威胁情报、漏洞检测、恶意软件检测、异常检测、模糊测试和程序修复、大型语言模型辅助攻击、（不）安全代码生成等。

• 威胁情报：从大量的威胁情报文档中提取信息非常困难。一些研究人员转而借助大型语言模型来整理和分析这些海量且杂乱的数据。 

• 漏洞检测：这是网络安全领域的一项关键任务，并且通过整合大型语言模型，已经出现了一些新颖的方法。 

• 恶意软件检测：大型语言模型既可以充当静态分析助手，也可以充当动态调试助手，从而提高该过程的效率和效果。 

• 异常检测：它主要指的是诸如网络流量中的恶意流量、系统中的病毒文件、日志中的异常情况等安全异常现象。 

表 2为网络安全领域所使用的大型语言模型概述

![image-20250314165720257](C:\Users\zds\AppData\Roaming\Typora\typora-user-images\image-20250314165720257.png)