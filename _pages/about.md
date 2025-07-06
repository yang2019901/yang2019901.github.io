---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

# 🎓 教育背景 {#Education}

**教育经历**

- *2023.09至今*：中国科学院自动化研究所，控制理论与控制工程，硕士学位在读。
- *2019.09 - 2023.06*：天津大学求是学部，自动化与数学双学位，理学和工学学士学位。

**个人能力**
-	**基于ROS的机器人系统的调试与开发**：较为熟练使用ROS及配套工具（rqt、rviz等），能够处理话题、服务的通信并据此搭建机器人软件框架。
-	**较为熟练掌握Pytorch**：能够独立完成深度学习模型的设计、训练与调优，具有图像分类、扩散模型拟合数据分布和表面肌电信号手势分类等多次实战经历。
-	**较为熟练掌握Unity引擎**，具备多次独立开发经历：曾独立编写2022届RMUC模拟器，实现了全兵种全功能全场地机制等上百页规则与UI系统、联机系统等；也曾搭建Unity+Python的强化学习仿真平台，及Unity+ROS的机械臂轨迹数据采集平台。
-	**对欠驱动机器人学有一定了解**：能够使用拉格朗日法建模，对全驱动系统应用反馈线性化解耦，以及对欠驱动机器人应用MPC或RL等控制方法（曾用casadi实现MPC完成Acrobot起摆/稳摆，以及PPO、SAC算法的应用经历）。
-	**较好的代码编写、调试和管理能力，以及基本的Linux系统管理和网络调试**：较为熟练掌握git，能根据工程规模使用vscode+debugpy进行侵入/非侵入式调试；掌握基本的Linux终端工具（熟练使用vim，理解正则表达式、管道与重定向，能够编写简单的bash自动化脚本），掌握基本的网络调试技能（netstat/telnet查/测端口状态、tcpdump抓包等及ip、iptables配sNAT和dNAT）。

**自我评价**
-	探索意识和钻研精神较强，对设计方案有**精益求精的追求**，有精细的时间管理意识，擅长规划时间，提高效率。
-	**热衷于拓宽能力边界**：喜欢接触新鲜而实用的技术，并动手完成实际项目以检验个人能力。
-	**坚持实证主义，致力于成为理论与实践并重的机器人工程师**：将实机测试贯穿于理论学习与研究，例如在RMUC能量机关击打任务和RMUA无人机定位任务中应用无迹卡尔曼滤波验证数字信号处理与随机过程的理论，在RMUS抓矿任务中应用反馈线性化控制验证现代控制理论和机器人学知识，且大多取得了较为出色的成绩。
-	**自律能力较好，抗压能力较强**：2024年度跑量超过2400公里，平均月跑量超过200公里，半程马拉松达标大众精英。


# 📝 学术成果 {#Publications}
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 25</div><img src='images/RMUS_paperbox.png' alt="RMUS overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Robotic Sim-to-Real Transfer for Long-Horizon Pick-and-Place Tasks in the Robotic Sim2Real Competition**

**Ming Yang**, Hongyu Cao, Lixuan Zhao, Chenrui Zhang, and Yaran Chen

[[paper](https://arxiv.org/abs/2503.11012)] [[code](https://github.com/yang2019901/GMatch)]

<strong><span class='show_paper_citations' data='XUaL4MMAAAAJ:qjMakFHDy7sC'></span></strong>

我们提出了一套自主机器人系统，可在长时序操作任务中实现仿真到现实（sim-to-real）的迁移。该系统的核心在于其感知与伺服模块，分别针对运动模糊和抓取模拟误差进行了鲁棒设计，从而在仿真和现实中一致地达到了亚厘米级的视觉伺服精度。
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/GMatch_paperbox.png' alt="GMatch overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GMatch: Geometry-Constrained Feature Matching for RGB-D Object Pose Estimation** 

**Ming Yang**, and Haoran Li

[[paper](https://arxiv.org/abs/2505.16144)] [[code](https://github.com/yang2019901/GMatch)]

<strong><span class='show_paper_citations' data='XUaL4MMAAAAJ:qjMakFHDy7sC'></span></strong>

本文提出了 GMatch，一种无需学习、运行高效的特征匹配算法，旨在实现鲁棒的 6DoF 物体位姿估计。GMatch 采用引导式增量搜索策略，并在整个过程中持续施加 SE(3) 不变的几何约束。作为一个通用特征匹配器，GMatch 可灵活适配主流关键点描述子，如 SIFT、SuperPoint 等。将 GMatch 与 SIFT 结合构建的位姿估计流程（即 GMatch-SIFT），在 BOP 基准平台中表现优异，达到或超过当前最佳算法的性能。
</div>
</div>

# 🏆 竞赛获奖 {#Awards}

## RoboMaster University Sim2Real Challenge (RMUS) 第一名，一等奖。

*2023.12-2024.05*

**比赛简介**：该比赛由 ICRA2024 主办，比赛内容是编程控制RoboMaster EP机器人在场地中自主搜寻矿石并在指定平台上按规定顺序尽可能高地码放。比赛包括仿真阶段，sim2real 阶段和最终评测。机器人的核心功能是亚厘米精度视觉伺服，核心难点是运动模糊克服和控制解耦。

**主要贡献**：
1. 基于 ArUco 和 LeNet 设计抗运动模糊的感知模块：ArUco 作为传统方形像素标签检测器具有快速性的特点，但基于模板的分类使其极易受运动模糊的影响，LeNet 作为学习类的图像分类器，能够通过数据集增广等方式提高鲁棒性达到极高的准确率。结合二者搭建感知模块，并通过拒识机制抵抗运动模糊，实现低于 1 ms 的推理延迟（NUC11 PAHi7）及 0.6 cm ／ 1.9 deg 的位姿估计精度（1 m 内）。
2. 基于反馈线性化设计非线性鲁棒的底盘伺服系统：针对立方体矿石斜向抓取侧滑的问题，将全向底盘的位置和姿态控制解耦以同时控制；通过系统辨识确定了纯延时、死区等非线性环节的参数并进行控制器仿真与设计，最终在实际中达到亚厘米级的伺服精度，高质量完成对所有矿石的抓取和堆叠。


## ROBOMASTER2022超级对抗赛 全国二等奖

*2020.08-2021.08*

**比赛简介**：该比赛是全国高校广泛参与的机器人对抗比赛。团队需要自主制作不同形态不同功能的机器人（步兵、英雄、哨兵、无人机、工程五种机器人）在复杂而机制丰富的场地上进行对抗，比赛团队规模约20-30人，分机械、电控和视觉算法三个部门。相关领域涵盖机械结构设计、嵌入式硬件开发和智能感知与控制等，对团队协作、进度管理、顶层设计和工程实现等多方面能力提出巨大挑战。我为视觉算法组成员，独立负责场地中能量机关的识别、预测和击打。

**主要贡献**：
1. 高效鲁棒的视觉识别算法：基于OpenCV设计算法提取视觉特征，并基于噪声模型创造性地应用时空信息进行滤波，在剧烈运动和严重光学干扰的场景下实现稳定的识别效果，而每帧耗时低于10ms。
2. 基于最优化/卡尔曼滤波的运动预测：建立能量机关的运动模型，先后实现了基于最优化和基于无迹卡尔曼滤波的两种运动参数估计的方案，并从收敛快速性、鲁棒性和时间开销等指标进行评估，最后使用ceres-solver（最优化方案）完成了运动参数估计及击打目标位置预测
3. 响应快速的云台控制与目标击打：基于视觉伺服思路以目标的图像坐标作为被控量设计PID控制器，建立高度补偿表并通过参数整定实现快速跟踪和击打，成功率达90%以上。

<!-- 
## 其余奖项
<div>
  <div style="display: flex; justify-content: space-between;">
    <span style="flex:1; text-align:left;">NITORI国际奖学金</span>
    <span style="flex:1; text-align:center;"><em>2021年</em></span>
    <span style="flex:1; text-align:right;"></span>
  </div>
  <div style="display: flex; justify-content: space-between;">
    <span style="flex:1; text-align:left;">全国大学生数学竞赛</span>
    <span style="flex:1; text-align:center;"><em>2020年</em></span>
    <span style="flex:1; text-align:right;">一等奖</span>
  </div>
  <div style="display: flex; justify-content: space-between;">
    <span style="flex:1; text-align:left;">ROBOMASTER 2021高校单项赛-工程采矿</span>
    <span style="flex:1; text-align:center;"><em>2021年</em></span>
    <span style="flex:1; text-align:right;">二等奖</span>
  </div>
  <div style="display: flex; justify-content: space-between;">
    <span style="flex:1; text-align:left;">全国大学生FPGA创新设计竞赛决赛</span>
    <span style="flex:1; text-align:center;"><em>2021年</em></span>
    <span style="flex:1; text-align:right;">二等奖</span>
  </div>
  <div style="display: flex; justify-content: space-between;">
    <span style="flex:1; text-align:left;">全国周培源大学生力学竞赛</span>
    <span style="flex:1; text-align:center;"><em>2021年</em></span>
    <span style="flex:1; text-align:right;">三等奖</span>
  </div>
  <div style="display: flex; justify-content: space-between;">
    <span style="flex:1; text-align:left;">中国高校智能机器人创意大赛</span>
    <span style="flex:1; text-align:center;"><em>2020年</em></span>
    <span style="flex:1; text-align:right;">三等奖</span>
  </div>
  <div style="display: flex; justify-content: space-between;">
    <span style="flex:1; text-align:left;">ROBOMASTER 2021高校联盟赛-3v3</span>
    <span style="flex:1; text-align:center;"><em>2021年</em></span>
    <span style="flex:1; text-align:right;">三等奖</span>
  </div>
</div>
 -->
# 🛠️ 项目经历 {#Projects}

## LoCoBot家居环境物品整理

*2024.09至今*

**项目简介**：在家居环境中导航，将散落的碗捡起并放回橱柜内。核心功能是抽屉的推拉和碗的抓取。

**主要贡献**
1. 构建语义导向的感知模块：以物体标签为输入，使用 Grounded SAM 分割 RGB 视图获取掩码，使用 GraspNet 生成掩码区域的抓取位姿估计。这构建了自然语言－掩码－抓取位姿的数据流，实现对任意物体的抓取位姿估计。
2. 基于 ROS 设计分布式程序：以 ROS Service 的形式封装感知模块 Grounded SAM 和 GraspNet，部署于工作站；轻量实时的导航和运动控制模块则运行于 LoCoBot 本体。
3. 改进机械臂的轨迹规划接口： 主流运动学规划软件 Moveit 只支持单目标点的规划，不能快速连续地经过多目标点。因此，我通过轨迹拼接与重规划，将间断式的规划加速为单次连续规划，显著节省运动耗时约 30％。

**工作成果**
1. 该工作以产品演示的形式被直接用于某具身智能初创公司的天使轮融资，占演示系统一半以上的权重。
2. 该工作促使了“几何约束的 SIFT 特征点匹配及快速位姿估计”的研究工作，其有效性和快速性在实际环境中通过验证，已送审 NIPS 2025。

## 基于强化学习的导航算法研究及其验证平台开发

*2023.03-2023.06*

**项目简介**：基于 Unity 引擎搭建仿真环境，模拟交互机制，并开发强化学习算法完成导航、对抗任务。核心功能是通过 ML－Agents 实现 Python 与 Unity 之间的强化学习数据接口。

**主要贡献**：
1. 基于 Unity 物理引擎模拟机器人运动和环境交互。
2. 基于 ML-Agents 插件实现 Python 和 Unity 的数据通信，并在 Python 端封装为强化学习环境接口。
3. 设计奖励函数并利用 PPO 实现端到端导航算法。

**工作成果**：用于本科毕业论文；仿真环境被直接用于课题组强化学习课程教学，亦被用于申请 ICRA2024 的 Workshop。

# 💻 个人作品 {#Portfolio}

## ROBOMASTER2022超级对抗赛模拟器 [[project](https://github.com/yang2019901/RMUC2022-Simulator-TJU)]

我于2022年7月开始自主研制RMUC2022模拟器。这既是为了挑战自我，想要拓宽个人能力边界；也是惊艳于华南理工大学2021年的模拟器，“欲与天公试比高”。

在此过程中，为了更加真实的车辆运动模拟、更简洁优雅的模块设计和代码实现，我从基础的Unity组件学起，继而去理解Unity场景物体的更新机制；为了更加精美的动画和UI效果、更高性能低延迟的多人联机方案，我从学习UI布局、动画以及UI和场景物体的联动，再到领悟如何抽取场景中最少的特征量、以最小化联机系统中场景同步的带宽需求。

通过一年的不懈努力，RMUC2022模拟器超额完成了预期目标，不仅以精简的代码量实现了上百页的规则手册，而且增添了诸如自动瞄准系统、超级电容等高级功能。源代码托管于Github，预构建的可执行程序可通过Release页面下载。

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Unity</div><img src='images/RMUC2022_battlefield.png' alt="RMUC2022 battlefield" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**基于Unity开发的RMUC2022模拟器**

*2022.07-2023.06*

- 基于Mirror插件实现多人联机系统，支持IPv6联机；
- 支持步兵、英雄、工程、无人机与哨兵及其全部功能；
- 支持云台自动瞄准系统，空中支援，工程车复活卡机制，超级电容等；
- 支持高地、飞坡等全部场地增益机制；
- 支持前哨站、基地、能量机关和兑换站等建筑。

</div>
</div>
