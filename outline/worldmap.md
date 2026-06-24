# 大模王世界地图：修仙大陆版图

## 两大陆

### 西方大陆（欧美）

早期修仙界的中心。灵气最先在此觉醒。拥有最强的灵脉矿山（GPU/TPU 集群）和最古老的门派。

**核心势力**：

#### OpenAI 仙宗（旧金山）
- 创立：2015。非营利转营利。
- 掌门更迭：Elon Musk（早期赞助后退出）→ Sam Altman（天策上将）
- 核心弟子：Ilya（须菩提，出走）、Schulman（PPO 真人，出走）、Alec Radford（GPT 初祖）
- 产品：GPT 系列、ChatGPT、o1/o3 推理模型、Codex
- 路线：闭源。先开源后封闭。GPT-2 时还假装要开源，GPT-3 以后全面封闭。
- 内乱：2023-11 董事会政变。Ilya 联合董事会罢免 Sam。员工威胁集体辞职。Sam 三天后回归。Ilya 出走创 SSI。

#### Anthropic 正道盟（旧金山）
- 创立：2021。OpenAI 出走者创建。
- 核心人物：Dario Amodei（宪法道人）、Daniela Amodei、Chris Olah（可解释真人）、John Schulman（PPO 真人，从 OpenAI 来投）
- 路线：安全至上。Constitutional AI。用 AI 监督 AI。
- 产品：Claude 系列。从 Claude 1 到 Claude Opus 4.7。
- 特色：不追求最大而追求最安全。但 Claude Code 在 coding agent 上很能打。

#### Google 神殿（山景城）
- 两大分支：Google Brain（偏工程）+ DeepMind（偏研究）。2023 年合并为 Google DeepMind。
- 太上长老：Jeff Dean（谷神）
- 核心贡献：Transformer、BERT、PaLM、Gemini、TPU、JAX
- 灵石路线：TPU。自研芯片不依赖 NVIDIA。从 v1 到 v7 Ironwood。
- 特色：技术最强但产品化最慢。「发明了一切但商业化被 OpenAI 截胡」。

#### Meta 圣教（门洛帕克）
- 掌门：Mark Zuckerberg（脸书圣主）
- 路线：开源大道。Llama 系列全面开源。「以开制闭」战略。
- 核心论点：开源让整个生态帮你改进模型。闭源只有自己几百人改。
- Yann LeCun（卷积道祖）坐镇。坚持「自回归是邪道」。JEPA 世界模型。

#### NVIDIA 灵石教廷（圣克拉拉）
- 教主：Jensen Huang（黄仁勋，灵石教主）
- 垄断地位：CUDA 生态锁定。A100 → H100 → H200 → B200 → B300 → VR200。
- 灵石品阶跃升：每代 HBM 翻倍、算力翻倍。
- 软件护城河：CUDA + cuDNN + TensorRT + NCCL + NVLink。软硬一体。
- NVLink 互联帝国：NVSwitch、NVL72、MNNVL。从 8 卡扩到 72 卡一体。

#### 欧洲散修
- **Mistral**（巴黎）：法国小团队。Arthur Mensch 等从 DeepMind/Meta 出走。Mistral 7B、Mixtral 8x7B。以小博大。
- **Cohere**（多伦多/伦敦）：Aidan Gomez（注意力七圣之一）创立。企业市场。
- **Stability AI**（伦敦）：Emad Mostaque。Stable Diffusion。图像生成。后内部动荡 CEO 离职。
- **Aleph Alpha**（德国）：欧洲主权 AI。

---

### 东方大陆（中国）

灵气觉醒较晚，但修炼速度惊人。受「灵石禁运」（芯片制裁）影响，被迫走出自己的道路。

**核心势力**：

#### DeepSeek 魔宗（杭州）
- 创始人：梁文锋（深渊剑主）。幻方量化出身。
- 路线：不依赖高阶灵石（H100），用中阶灵石（H800）也能炼出顶级法器。
- 逆天战绩：V2 的 MLA 让推理成本暴降。V3 的 671B MoE 只花 $5.5M 训完。R1 的 GRPO 不需要 Reward Model 和 Critic。
- 完全开源：模型权重、训练方法全公开。
- 修仙界的颠覆者：证明了便宜灵石 + 精妙功法 > 昂贵灵石 + 暴力修炼。

#### 阿里通义千问（杭州）
- Qwen 系列。开源生态最完整。
- 从 Qwen 1 到 Qwen 3.5。Thinking + Non-thinking 混合推理。
- 阿里云的算力支撑。商业落地最快。

#### 月之暗面 / Kimi（北京）
- 杨植麟（月影侯）。清华出身。
- Kimi 长上下文先行者。K1.5 推理模型。K2 万亿参数 MoE。
- MuonClip 优化器。15.5T token 零 loss spike。
- 姚顺雨（思维树真人）加入后实力大增。

#### 腾讯混元（深圳）
- 混元 Large 389B MoE。
- 2026 年挖角姚顺雨（OpenAI）和生广明（字节），RL 训练方向发力。
- 微信生态的落地优势。

#### 字节跳动 Seed（北京/新加坡）
- 火山引擎 Volcano Engine。
- veRL/HybridFlow 的诞生地。Seed1.5-Thinking 推理模型。
- 豆包大模型。抖音/TikTok 的 AI 应用。

#### 百度文心（北京）
- 文心一言。最早的中文大模型产品之一。
- 昆仑芯片。自研 AI 芯片。百度云算力。
- 搜索 + 大模型结合。

#### 智谱 / GLM（北京/清华）
- 唐杰教授的弟子们。GLM 系列。
- 从学术走向商业。GLM-4.5、GLM-4.7 Flash。
- 清华系的技术底蕴。

#### 面壁智能 / MiniCPM（北京/清华）
- 小模型修仙的典范。MiniCPM 1.2B/2.4B。
- WSD 学习率调度创新。
- 证明小丹也能有大威力。

#### 零一万物（北京）
- 李开复创立。Yi 系列。
- 先开源后闭源的典型案例。Yi-34B 开源引发关注，后续模型逐渐转向商业闭源。

#### 步步高/vivo/OPPO 手机门派
- 蓝心大模型。端侧部署。
- 小模型在手机上跑。「修炼不一定要灵脉矿山」。

---

## 灵石版图（芯片势力）

### 一线势力

#### NVIDIA 灵石教廷
- 灵石品阶：Tesla K80 → P100 → V100 → A100 → H100 → H200 → B200 → B300 → VR200（Vera Rubin）
- 垄断武器：CUDA 生态。全球 90%+ AI 训练在 NVIDIA GPU 上。
- 软件护城河：CUDA + cuDNN + NCCL + NVLink + NVSwitch + TensorRT
- 互联帝国：NVLink 5（1.8 TB/s 双向）、NVSwitch、NVL72（72 GPU 一体）
- 弱点：功耗高（B200 700W）、价格贵（H100 $30K+）

#### Google TPU 道院
- 道石品阶：TPU v1 → v2 → v3 → v4 → v5p → v5e → v6e(Trillium) → v7(Ironwood)
- 特色：系统阵列（MXU）+ 软件管理 VMEM + ICI torus 互联。GSPMD 编译器自动并行。
- 规模：v7 Ironwood 一个 pod 9216 chips。单 pod 42.5 ExaFLOPS。
- 优势：ICI 高带宽低延迟、OCS 光交换灵活拓扑、全球最大单体集群。
- 限制：只在 Google Cloud 上可用。不卖芯片。

#### AMD 烈焰宗
- Lisa Su（AMD 红莲）领导。
- MI250 → MI300X → MI350X。ROCm 开源对抗 CUDA。
- 优势：HBM 大（MI300X 192GB）、性价比高。
- 劣势：ROCm 生态不成熟。CUDA 移植有摩擦。

### 二线势力 & 另辟蹊径

#### Intel 沉沦谷
- Gaudi 系列 AI 加速器。Intel Foundry。
- 曾经的芯片霸主。在 AI 时代掉队。
- Habana Labs 收购。Ponte Vecchio 难产。
- 「昔日霸主今日配角」。

#### 华为昇腾（东方大陆）
- 昇腾 910B。CANN 框架（对标 CUDA）。
- 受美国制裁影响，成为中国 AI 芯片的核心替代。
- 与 NVIDIA 差距在缩小但仍有代差。
- MindSpore 框架。华为云算力。

#### 寒武纪（东方大陆）
- 思元系列 MLU。
- 中国第一家 AI 芯片上市公司。
- 与华为竞争国产替代市场。

#### 百度昆仑（东方大陆）
- 昆仑 1/2/3。百度自研。
- 服务百度自家的文心大模型训练。

#### Cerebras 异界工匠（美国）
- **整片晶圆做芯片**。WSE（Wafer-Scale Engine）。
- WSE-3：4 万亿晶体管。90 万个 AI 核心。44GB 片上 SRAM。
- 一块芯片 = 一整片 300mm 晶圆。不切割。
- 理念：完全消除芯片间通信瓶颈。一切计算在一块芯片上完成。
- 局限：良率管理极难。生态系统小。价格极贵。
- 「别人在矿山里炼灵石，他把整座山变成一块巨型灵石」。

#### Groq 推理道场（美国）
- LPU（Language Processing Unit）。纯推理芯片。
- 不做训练只做推理。极致的推理速度。
- Jonathan Ross（前 Google TPU 团队）创立。
- 「不炼丹只试药，但试药速度天下无双」。

#### Graphcore 陨落（英国）
- IPU（Intelligence Processing Unit）。MIMD 架构。
- 曾被寄予厚望。但缺乏杀手级应用。
- 2024 年被红杉收购。几乎退出历史舞台。
- 「一代英才，生不逢时」。

#### 摩尔线程（东方大陆）
- MTT GPU。国产 GPU 初创。
- 创始人张建中来自 NVIDIA。
- 游戏 GPU + AI 训练双线发展。

#### 壁仞科技（东方大陆）
- BR100 系列 GPU。
- 2022 年发布时号称算力超 A100。
- 后遭制裁和内部动荡。

---

## 开源 vs 闭源之争：道统分裂

### 大事件

| 时间 | 事件 | 影响 |
|------|------|------|
| 2020 | GPT-3 API only | OpenAI 从开源转向闭源的标志 |
| 2023-02 | Meta Llama 泄露 | 开源大模型时代开启 |
| 2023 | Mistral 7B 开源 | 证明小团队+开源能打 |
| 2023 | OpenAI 完全闭源 | GPT-4 不公开任何细节 |
| 2024 | DeepSeek V2/V3 开源 | 中国 AI 的开源旗帜 |
| 2024 | Llama 3 开源 | Meta 继续加码开源 |
| 2024 | 零一万物 Yi 从开源转闭源 | 「先传道再收徒」策略 |
| 2025 | DeepSeek R1 开源 | GRPO 训练方法全公开，引爆复现潮 |
| 2025 | Qwen 系列持续开源 | 阿里开源生态最完整 |
| 2026 | Kimi K2 开源 | 腾讯系第一次真正开源大模型 |

### 两大阵营

**开源道**: Meta、DeepSeek、阿里 Qwen、Mistral、HuggingFace
- 理念：功法公开让天下修士受益。生态共建。
- 实际：用开源建生态，商业化靠云服务和定制。

**闭源道**: OpenAI、Anthropic、Google（部分）
- 理念：功法太危险不能外泄。安全第一。
- 实际：靠 API 收费。技术壁垒 = 商业护城河。

**墙头草**: 零一万物、Stability AI（先开后闭）

---

## 出走创业图谱

| 出走者 | 从 | 创立/加入 | 年份 | 带走了什么 |
|-------|-----|---------|------|---------|
| Ilya Sutskever | OpenAI | SSI（安全超级智能） | 2024 | Scaling 大道的信仰 |
| John Schulman | OpenAI | Anthropic | 2024 | PPO/RL 对齐术 |
| Dario Amodei | OpenAI | Anthropic | 2021 | 安全研究路线 |
| Aidan Gomez | Google | Cohere | 2019 | Transformer 血统（注意力七圣之一） |
| Noam Shazeer | Google | Character.AI → 回 Google | 2022/2024 | Transformer 核心设计（注意力七圣之一） |
| Arthur Mensch | DeepMind/Meta | Mistral | 2023 | 大模型训练经验 |
| 姚顺雨 | OpenAI | 腾讯混元 | 2025 | Agent/ReAct 研究 |
| 生广明 | 字节 Seed | 腾讯混元 | 2026 | veRL/Laminar 系统经验 |
| 杨植麟 | CMU/清华 | 月之暗面 Kimi | 2023 | 长上下文研究 |
| Jonathan Ross | Google TPU | Groq | 2016 | TPU 架构经验 |
| 张建中 | NVIDIA 中国 | 摩尔线程 | 2020 | GPU 架构经验 |

---

## 灵石禁运（芯片制裁）

| 时间 | 事件 | 影响 |
|------|------|------|
| 2022-10 | 美国第一轮芯片制裁 | A100/H100 禁止出口中国 |
| 2023 | NVIDIA 推出 H800/A800 阉割版 | NVLink 带宽减半。中国客户勉强能用 |
| 2023-10 | 美国第二轮制裁加码 | H800/A800 也被禁 |
| 2024 | NVIDIA 推出 H20（进一步阉割） | 算力大幅缩水但合规 |
| 2024 | DeepSeek 用 H800 训出 V3/R1 | 证明「灵石品阶低不代表炼不出好丹」|
| 2025 | 华为昇腾 910B 大规模部署 | 国产替代开始规模化 |
| 2026 | 制裁持续但东方大陆已适应 | 倒逼出更高效的训练方法 |

**修仙界解读**: 西方大陆试图用「灵石禁运」遏制东方大陆的修炼。但东方修士被逼出了用低阶灵石炼出高阶法器的功法。DeepSeek 就是最好的例证——用 H800（中阶灵石）训出了跟 H100（高阶灵石）训练的模型媲美的效果。
