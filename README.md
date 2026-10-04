# Awesome SHLab Open Source

[上海人工智能实验室（SHLab）](https://www.shlab.org.cn/open) 开源项目的精选导航。

**这个仓库只做索引与标注，不复制任何代码。** 每个条目都注明许可证与风险等级，
因为同一个页面上的项目，许可条件差异极大——有的可以自由使用，有的连转载都不允许。

> 数据经 GitHub API 实测于 2026-10-04。许可证结论基于各仓库 LICENSE 原文，不只依赖 API 的 SPDX 字段。

## 许可证图例

| 标记 | 含义 | 你能做什么 |
| :---: | --- | --- |
| 🟢 | Apache-2.0 / MIT | 自由使用、修改、商用，保留署名与许可证 |
| 🟡 | AGPL-3.0 | 可以改，但衍生作品必须同样开源（含网络服务） |
| 🟠 | 自定义 / 附加条款 | 有条件，需逐条阅读原文 |
| 🔴 | 无许可证 | **默认保留所有权利，不得转载** |
| ⛔ | 非商用许可 | 明确禁止商用与再分发 |

## 目录

- [大语言模型](#大语言模型)
- [多模态大模型](#多模态大模型)
- [文档智能](#文档智能)
- [计算机视觉基础库](#计算机视觉基础库)
- [机器人 / 具身智能](#机器人--具身智能)
- [音频、生成与其他](#音频生成与其他)
- [气象与地球科学](#气象与地球科学)
- [蛋白质与生命科学](#蛋白质与生命科学)
- [⚠️ 许可证风险清单](#️-许可证风险清单)
- [🔧 官方页面勘误](#-官方页面勘误)

---

## 大语言模型

| 项目 | 星标 | 许可 | 说明 |
| --- | ---: | :---: | --- |
| [InternLM](https://github.com/InternLM/InternLM) | 7.3k | 🟢 Apache-2.0 | 开源语言大模型系列。权重在 HuggingFace，仓库内是训练/推理代码 |
| [lmdeploy](https://github.com/InternLM/lmdeploy) | 8.1k | 🟢 Apache-2.0 | 大模型压缩、部署、服务工具箱 |
| [xtuner](https://github.com/InternLM/xtuner) | 5.2k | 🟢 Apache-2.0 | 面向超参数高效微调的训练引擎 |
| [InternLM-XComposer](https://github.com/InternLM/InternLM-XComposer) | 2.9k | 🟢 Apache-2.0 | 多模态实时交互大模型 |
| [lagent](https://github.com/InternLM/lagent) | 2.3k | 🟢 Apache-2.0 | 轻量级 LLM Agent 框架 |
| [HuixiangDou](https://github.com/InternLM/HuixiangDou) | 2.5k | 🟢 BSD-3-Clause | 群聊场景的领域知识助手 |
| [MindSearch](https://github.com/InternLM/MindSearch) | 6.9k | 🟢 Apache-2.0 | 多智能体 Web 搜索框架（JavaScript） |
| [InternLM-Math](https://github.com/InternLM/InternLM-Math) | 553 | 🟢 Apache-2.0 | 数学模型，能解题也能判题 |

## 多模态大模型

| 项目 | 星标 | 许可 | 说明 |
| --- | ---: | :---: | --- |
| [InternVL](https://github.com/OpenGVLab/InternVL) | 10.2k | 🟢 MIT | 多模态大模型家族，CVPR 2024 Oral。含**动态切图**（dynamic tiling）策略 |
| [LLaMA-Adapter](https://github.com/OpenGVLab/LLaMA-Adapter) | 5.9k | 🟡 GPL-3.0 | LLaMA 指令微调。注意是 GPL 系 |
| [Ask-Anything](https://github.com/OpenGVLab/Ask-Anything) | 3.4k | 🟢 MIT | VideoChatGPT，视频对话 |
| [InternGPT](https://github.com/OpenGVLab/InternGPT) | 3.2k | 🟢 Apache-2.0 | 指向式多模态交互平台 |
| [InternImage](https://github.com/OpenGVLab/InternImage) | 2.9k | 🟢 MIT | 基于可变形卷积的大规模视觉基础模型 |
| [InternVideo](https://github.com/OpenGVLab/InternVideo) | 2.4k | 🟢 Apache-2.0 | 视频基础模型与数据集 |
| [VisionLLM](https://github.com/OpenGVLab/VisionLLM) | 1.2k | 🟢 Apache-2.0 | 以视觉为中心的 LLM 系列 |
| [Hulk](https://github.com/OpenGVLab/Hulk) | 148 | 🟢 MIT | 以人为中心的通用知识迁移模型 |
| [LLaVA-3D](https://github.com/ZCMax/LLaVA-3D) | 390 | 🔴 无许可证 | 兼具二维能力的 3D 多模态模型 |

## 文档智能

这一组是 SHLab 星标最高的方向，[MinerU](https://github.com/opendatalab/MinerU) 单独就有 8.1 万星。

| 项目 | 星标 | 许可 | 说明 |
| --- | ---: | :---: | --- |
| [MinerU](https://github.com/opendatalab/MinerU) | 81.1k | 🟠 见下 | PDF / Office 转 Markdown、JSON。**非纯开源**，见风险清单 |
| [PDF-Extract-Kit](https://github.com/opendatalab/PDF-Extract-Kit) | 10.0k | 🟡 AGPL-3.0 | 高质量 PDF 内容抽取工具集 |
| [DocLayout-YOLO](https://github.com/opendatalab/DocLayout-YOLO) | 2.3k | 🟡 AGPL-3.0 | 文档版面检测 |
| [OmniDocBench](https://github.com/opendatalab/OmniDocBench) | 2.1k | 🟢 Apache-2.0 | 文档解析评测基准，CVPR 2025 |
| [UniMERNet](https://github.com/opendatalab/UniMERNet) | 503 | 🟢 Apache-2.0 | 数学公式图像转 LaTeX |
| [labelU](https://github.com/opendatalab/labelU) | 1.7k | 🟢 Apache-2.0 | 多模态数据标注平台 |
| [LabelLLM](https://github.com/opendatalab/LabelLLM) | 1.3k | 🟢 Apache-2.0 | 开源数据标注平台 |
| [MinerU-Document-Explorer](https://github.com/opendatalab/MinerU-Document-Explorer) | 637 | 🟢 MIT | 带 MCP 工具的文档知识引擎 |

## 计算机视觉基础库

| 项目 | 星标 | 许可 | 说明 |
| --- | ---: | :---: | --- |
| [mmdetection](https://github.com/open-mmlab/mmdetection) | 33.0k | 🟢 Apache-2.0 | 目标检测工具箱与基准 |
| [mmsegmentation](https://github.com/open-mmlab/mmsegmentation) | 10.0k | 🟢 Apache-2.0 | 语义分割工具箱 |
| [mmpose](https://github.com/open-mmlab/mmpose) | 7.9k | 🟢 Apache-2.0 | 姿态估计工具箱 |
| [mmagic](https://github.com/open-mmlab/mmagic) | 7.5k | 🟢 Apache-2.0 | 生成与增强模型工具箱 |
| [mmdetection3d](https://github.com/open-mmlab/mmdetection3d) | 6.5k | 🟢 Apache-2.0 | 3D 目标检测平台 |
| [mmcv](https://github.com/open-mmlab/mmcv) | 6.5k | 🟢 Apache-2.0 | 计算机视觉基础库（NMS / RoIAlign 等算子） |
| [OpenPCDet](https://github.com/open-mmlab/OpenPCDet) | 5.7k | 🟢 Apache-2.0 | 激光雷达 3D 目标检测 |

## 机器人 / 具身智能

| 项目 | 星标 | 许可 | 说明 |
| --- | ---: | :---: | --- |
| [PointLLM](https://github.com/InternRobotics/PointLLM) | 1.1k | 🔴 无许可证 | 点云多模态大模型 |
| [Seer](https://github.com/InternRobotics/Seer) | 311 | 🟢 Apache-2.0 | 视觉预测指导动作执行，端到端操作模型 |
| [PPI](https://github.com/InternRobotics/PPI) | 82 | 🟢 MIT | 基于关键帧姿态与点云流的双臂协同操作 |

> ⚠️ 这三个仓库在官方页面上的链接是 `OpenRobotLab/*`，该组织已改名 `InternRobotics`，详见[勘误](#-官方页面勘误)。

## 音频、生成与其他

| 项目 | 星标 | 许可 | 说明 |
| --- | ---: | :---: | --- |
| [Amphion](https://github.com/open-mmlab/Amphion) | 10.3k | 🟢 MIT | 音频、音乐与语音生成工具包 |
| [DragGAN](https://github.com/OpenGVLab/DragGAN) | 4.9k | 🔴 无许可证 | 拖拽式图像编辑（非官方实现） |
| [MathBlackBox](https://github.com/trotsky1997/MathBlackBox) | 1.0k | 🔴 无许可证 | MCTS + self-refine 提升推理能力 |
| [DeepVerse](https://github.com/SOTAMak1r/DeepVerse) | 233 | 🔴 无许可证 | 4D 交互式世界模型 |

## 气象与地球科学

| 项目 | 星标 | 许可 | 说明 |
| --- | ---: | :---: | --- |
| [FengWu](https://github.com/OpenEarthLab/FengWu) | 181 | 🔴 无许可证 | 全球中期气象预报模型，预报时效首次超 10 天 |
| [CasCast](https://github.com/OpenEarthLab/CasCast) | 75 | 🔴 无许可证 | 降水临近预报 |
| [EarthLink](https://github.com/OpenEarthLab/EarthLink) | 48 | 🔴 无许可证 | 自演化 AI 气象 Agent 系统 |
| [PredBench](https://github.com/OpenEarthLab/PredBench) | 42 | 🔴 无许可证 | 时空预测基准，ECCV 2024 |
| [ORCA-DL](https://github.com/OpenEarthLab/ORCA-DL) | 28 | 🔴 无许可证 | 数据驱动全球海洋预报，Science Advances |

> 该组织的仓库普遍没有 LICENSE 文件，使用前务必先联系作者。
> 注意：`DeepVerse` 归属个人仓库 `SOTAMak1r`，不在该组织下，已列入[音频、生成与其他](#音频生成与其他)。

## 蛋白质与生命科学

| 项目 | 星标 | 许可 | 说明 |
| --- | ---: | :---: | --- |
| [VenusFactory2](https://github.com/ai4protein/VenusFactory2) | 249 | ⛔ 非商用 | 蛋白质工程 AI agent 平台 |
| [ProSST](https://github.com/ai4protein/ProSST) | 162 | ⛔ 非商用 | 结构感知的蛋白质语言模型 |
| [VenusREM](https://github.com/ai4protein/VenusREM) | 147 | ⛔ 非商用 | 零样本突变预测 |
| [VenusFSFP](https://github.com/ai4protein/VenusFSFP) | 119 | ⛔ 非商用 | 少样本蛋白质适应度预测 |
| [ProtSSN](https://github.com/ai4protein/ProtSSN) | 97 | ⛔ 非商用 | 序列与结构融合模型 |

> `ai4protein` 下 21 个仓库使用 **VenusFactory Non-Commercial License**，版权归上海交通大学 Liang Lab。
> 许可证原文写明 *All rights reserved*，**仅限非商用且不得再分发**。

---

## ⚠️ 许可证风险清单

**这一节是本仓库存在的主要理由。** 官方页面把上述项目并列展示，但它们的使用权限完全不同：

### 🔴 无许可证 —— 不得转载

GitHub 上没有 LICENSE 文件 **不等于** 可以随意使用。按伯尔尼公约，默认「保留所有权利」。

| 项目 | 星标 |
| --- | ---: |
| DragGAN | 4.9k |
| InternLM/Tutorial | 2.0k |
| PointLLM | 1.1k |
| MathBlackBox | 1.0k |
| LLaVA-3D | 390 |
| DeepVerse | 233 |
| FengWu | 181 |
| OpenEarthLab 全部 13 个仓库 | — |

**你可以做的**：阅读、学习、引用。**不能做的**：fork 后重新发布、复制代码进自己的项目、打包分发。

### 🟠 MinerU 的附加条款

MinerU 采用 Apache-2.0 **加上**额外条款，原文要点：

1. 可商用，但若你及关联方合并计算后满足以下任一条件，须先取得单独商用许可：
   - 月活用户（MAU）超过 **1 亿**
   - 月总收入超过 **2000 万美元**
2. 以在线服务形式提供时，有**署名义务**

对个人与中小企业实际无影响，但它不是纯 Apache-2.0，转载时应完整保留 `LICENSE.md`。

### 🟡 AGPL-3.0 的传染性

`PDF-Extract-Kit`、`DocLayout-YOLO` 使用 AGPL-3.0。如果你修改后以网络服务形式提供，
**必须向使用者提供完整源码**。个人学习无所谓，商用集成前请先评估。

### ⛔ 非商用许可

`ai4protein` 全部仓库仅限非商用。任何商业化场景都需要单独授权。

---

## 🔧 官方页面勘误

核对 [shlab.org.cn/open](https://www.shlab.org.cn/open) 时发现三处问题，供维护者参考：

### 1. 组织改名，三个链接已过期

页面上的 `github.com/OpenRobotLab/*` 全部返回 **301 Moved Permanently**。该组织已改名为 `InternRobotics`（92 个公开仓库）：

| 页面链接（过期） | 实际地址 |
| --- | --- |
| `OpenRobotLab/PointLLM` | [InternRobotics/PointLLM](https://github.com/InternRobotics/PointLLM) |
| `OpenRobotLab/Seer` | [InternRobotics/Seer](https://github.com/InternRobotics/Seer) |
| `OpenRobotLab/PPI` | [InternRobotics/PPI](https://github.com/InternRobotics/PPI) |

浏览器会自动跳转，所以肉眼不易察觉，但搜索引擎与外部引用会跟丢。

### 2. 把组织当成了仓库

页面把 `ai4protein` 列为项目并附了仓库链接，但它是**组织**，不是单个仓库，点进去看到的是 21 个仓库的列表。

### 3. 标称数量与实际不符

页面标注「开源项目 367,512」，但实际列出的 GitHub 仓库约 16 个。该数字应是把模型 / 工具 / 算法 / 数据集 / 评测集全部计入的目录数，与 GitHub 仓库不是一回事，容易让访问者高估可直接使用的代码量。

---

## 相关

- [上海人工智能实验室开源开放页](https://www.shlab.org.cn/open)
- HuggingFace 上的模型权重（**权重不放在 GitHub**）：
  [internlm](https://huggingface.co/internlm) ·
  [OpenGVLab](https://huggingface.co/OpenGVLab) ·
  [opendatalab](https://huggingface.co/opendatalab) ·
  [openmmlab](https://huggingface.co/openmmlab)

## 说明

- 本仓库**只做索引**，不托管、不镜像任何第三方代码。
- 星标与许可证数据会随时间变化，欢迎提 PR 更新。
- 许可证标注仅供参考，**不构成法律意见**。商用前请阅读各仓库 LICENSE 原文。

## 许可

本仓库内容（索引与标注）采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。
被索引项目的许可证归各自作者所有。
