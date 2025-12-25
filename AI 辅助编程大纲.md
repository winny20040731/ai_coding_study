# 使用的工具

## AI PPT

使用https://www.chatppt.cn/   感觉一般

使用https://ppt.quark.cn/  夸克PPT，直接使用 chatgpt 输出的 md 制作，一致性保持的还可以，PPT 中突出不了重点

豆包中制作PPT

百度文库 PPT 制作不接受 md 文件，把 md 转换为 pdf，把 md 文件中文本内容直接放到输入框中，有字数限制 5000；

参考《AI+Coding+课程讲稿（精简版·Markdown）.pptx》



### **三大核心方案**

- **图片生成式**：输入内容后 AI 直接生成 PPT 图片，原理是 AI 根据用户需求规划图片内容并保持背景一致、排版合理，对图片一致性和文本能力要求高，Nano Banana Pro 推出后效果提升。以 NotebookLM 为例，使用时只需上传信息点击按钮，优点是无需过多准备资料、速度快、成本低，缺点是内容调整困难；未来 Gemini 原生多模态模型或让该方案更可控、易修改，成为趋势。
- **网页编程式**：通过 AI 编程生成网页实现 PPT 效果，与代码转视频原理相似，效果受模型和提示词影响大。优点是内容调整便捷（基于代码）、支持动效、数据呈现精准（如曲线图），目前是较受看好的方案，优化后可结合绘图模型提升效果。
- **模板式**：出现时间较早，部分采用该方案的网站已盈利，原理是 AI 整理内容并填入预设 PPT 模板，如 Gamma、AiPPT 等，通过工程优化（智能选模板、区块调节）提升效果。优点是可控性强、用户体验好，缺点是实现难度高于前两种方案，开源项目 PPTAgent（GitHub 2300 星且持续更新）可参考，其采用 “学习示例 PPT 布局结构 - 生成新幻灯片” 的两阶段编辑式流程。



## 纳米香蕉模型

**Nano Banana Pro**（官方正式名称为 **Gemini 3 Pro Image**）时，建议将其定位为“**从‘绘画工具’向‘生产力工具’跨越的里程碑模型**”。

可以使用它做知识可视化，对学习会有很大的帮忙

![image-20251223082838852](/Users/paulxu/Library/Application Support/typora-user-images/image-20251223082838852.png)

![image-20251223083716148](/Users/paulxu/Library/Application Support/typora-user-images/image-20251223083716148.png)

![Image](https://pbs.twimg.com/media/G6OnbMzbAAABomT?format=jpg&name=large)

![Image](https://pbs.twimg.com/media/G6wwAdDXwAA8trb?format=jpg&name=medium)

![Image](https://pbs.twimg.com/media/G6s3MZXWQAAuBRO?format=jpg&name=4096x4096)



## AI知识管理工具

### notebookLM

工具：谷歌notebookLM

网址：***https://notebooklm.google.com/\***

![图片](https://mmbiz.qpic.cn/mmbiz_png/rVsHjPxgtk2I6YezpPFx7AXX1cOS2K3qstZiaECXYgc3VeUtnD4aoUU8WRa39ULWMfmlhoefictndVzU77Ne3MZw/640?wx_fmt=png&from=appmsg&watermark=1&tp=wxpic&wxfrom=5&wx_lazy=1#imgIndex=0)



Google Labs 的总监 Steven Johnson 在演示中特别强调了 NotebookLM 的界面逻辑。它完美契合了 IPO模型：Input（输入）、Process（处理）、Output（输出）。

当你打开它，你会看到一个清晰的三栏式布局。我把它比喻为一个数字化的书房。

![image-20251222132641710](/Users/paulxu/Library/Application Support/typora-user-images/image-20251222132641710.png)





### 腾讯ima与Get笔记

![图片](https://mmbiz.qpic.cn/mmbiz_png/p69qCYb67zpHxtCLbQj0nId33b8EDpR4lelDTBXFo88DNrvOvdpdibwmoiarrNUqhxub8XYxuUlJKDrOaYQicnkAA/640?wx_fmt=png&from=appmsg&tp=wxpic&wxfrom=5&wx_lazy=1#imgIndex=4)





**功能对比总表**：

| **能力维度** | **腾讯ima**       | **Get笔记**      |
| ------------ | ----------------- | ---------------- |
| 知识收集     | 微信生态深度整合  | 多模态输入覆盖全 |
| 知识输出     | 专业内容创作强    | 日常优化优秀     |
| 团队协作     | 权限管理逐渐丰富  | 基础分享功能     |
| 大文件处理   | 千页文档解析      | 碎片内容优化     |
| 免费存储     | 30G个人+共享      | 30G免费版        |
| 知识生态     | 知识库广场+知识号 | 知识库广场       |

# AI 辅助编程介绍

请参考使用 notebookLM 制作的文档《AI编程_新现实与工程未来.pdf》

![image-20251222231513340](/Users/paulxu/Library/Application Support/typora-user-images/image-20251222231513340.png)



| **阶段 (Stages)**       | **核心定义与范式**                                           | **2025 年末代表工具 (附 Logo 描述)**                         |
| ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **L4: 意图/氛围编程**   | **“只需意图，无需代码”**。用户管理审美与逻辑，AI 负责全栈实现与部署。 | **Lovable**, **v0.dev**, **Bolt.new**, **Replit Agent**      |
| **L3: 自主 Agent 编程** | **“任务导向，闭环执行”**。AI 拥有终端权限，能自主运行、测试、修复 Bug。 | **Claude Code**, **GPT-5.2-Codex**, **Aider**, **OpenHands** |
| **L2: 原生 AI IDE**     | **“全量感知，重塑环境”**。IDE 本身就是 AI，理解整个代码库的深度上下文。 | **Cursor**, **Windsurf**, **Trae (字节)**, **Zed AI**        |
| **L1: 辅助补全插件**    | **“传统增强，单点优化”**。在 VS/JetBrains 中作为插件存在，稳健安全。 | **GitHub Copilot**, **通义灵码 (Aliyun)**, **Amazon Q**      |
| **底层大脑 (Brains)**   | **“推理与逻辑的源动力”**。2025 年末的最强 SOTA 模型。        | **Claude Opus 4.5**, **GPT-5.2 Pro**, **Gemini 3**, **DeepSeek R1** |



![image-20251222234230518](/Users/paulxu/Library/Application Support/typora-user-images/image-20251222234230518.png)



![image-20251222234953416](/Users/paulxu/Library/Application Support/typora-user-images/image-20251222234953416.png)

# AI 编程工具-Claude Code介绍 

请参考使用notebookLM制作的文档《Mastering_Claude_Code.pdf》

## 内部安装与配置

to-do 待补充



# 案例-- api mock 服务

请参考《api_mock_server_demo.pdf》文档，介绍 SDD/TDD 使用

在已有项目中使用案例 --前端的配置页面/ 后端通过 api 获取数据

# 总结

