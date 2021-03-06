# 第一章 总纲

## 1. 开放运维联盟介绍
开放运维联盟（OOPSA）成立于2015年10月31日，2015 GOPS：全球运维大会·上海站。在现场八百名运维同仁的共同见证下，开放运维联盟指导单位数据中心联盟（DCA）常务副理事长何宝宏博士、秘书长孙明俊女士，和开放运维联盟的六位联合发起人共同点亮启动球。

OOPSA 的六位联合发起人均为运维资深从业人士，其中既有一线大厂如BAT 多年工作经验的专家人士，也有近年来运维行业的思考者、布道者、运维自媒体。这些发起者的共同特点是，深植于运维，深知其中疾苦；深爱着运维，希望和广大运维同仁们一起，共同成长。

OOPSA 的成立，得益于微信及这个时代。来自高效运维、互联网运维杂谈和数据中心操作系统等微信公众号的众多高质量技术原创文章，吸引了大量志同道合的同仁。于是，大家汇聚，相识、相知。

![](http://7xl5e0.com1.z0.glb.clouddn.com/C1%200001.png)

图片地址：http://7xl5e0.com1.z0.glb.clouddn.com/C1%200001.png 

开放运维联盟想汇聚行业的力量与智慧，从运维最佳实践、运维规范开始，一步一步，从内而外，开展工作。互联网行业可能会消失，但运维不会消失，希望运维可以见证并助力传统企业融合互联网的全过程。

![](http://7xl5e0.com1.z0.glb.clouddn.com/C10002.png)

图片地址：http://7xl5e0.com1.z0.glb.clouddn.com/C10002.png

开放运维联盟下设多个工作组，包括应用运维工作组、云运维工作组及大数据运维工作组等，以分别及协同开展工作。

## 2. 应用运维工作组介绍
本工作组目前由以下成员组成（按字母序）：

- 刘栖桐（腾讯互娱运维负责人，智能运维提出方）
- 梁定安（腾讯SNG空间运维负责人）
- 徐奇琛（京东无线运维总监）
- 孙宇聪（coding.net CTO，原Google SRE）
- 王津银（优维科技创始人，精益运维提出者）
- 涂彦（腾讯互娱运维总监，智能运维提出方）
- 萧田国（触控科技总监，高效运维提出者）

这七位同学分别来自于游戏、搜索、电商、社交这几大互联网应用的领域，基本可以代表目前主要方向上的互联网应用，他们的经验可以提取一些通用的东西出来，能够普惠于整个互联网行业的运维。

## 3. 互联网应用运维涵括范围
**应用运维是做什么的？**
![](http://7xl5e0.com1.z0.glb.clouddn.com/C10003.png)

图片地址：http://7xl5e0.com1.z0.glb.clouddn.com/C10003.png


用运维就是支持每个公司应用系统的运维，这些应用系统有一些是直接对外提供服务，为公司直接创造价值的，最典型的例子，比如游戏或者电商的网站等等。

还有一些可能不直接创造价值，但是对于公司来说是非常重要的系统，比如通信行业，电信对外服务的网站，这也是非常重要的应用系统。那么，维护这些系统就叫应用运维。

应用运维的价值是要服务于业务，帮助业务实现价值的最大化。要么就是帮助业务赚更多的钱，要么就是帮助业务提供更好的服务给业务的用户，从而为业务创造更大的价值。

因此，应用运维相比于传统的网络运维、IT运维要更贴近业务一些，**所以应用运维模式就是要贴近业务、理解业务，进而进一步挖掘业务背后的价值，最后进一步扩展服务的价值。**

## 4. 互联网应用运维标准产生背景
为什么要做互联网应用运维框架和能力模型？

大家都很熟悉ITIL，运维领域在这之前一直流行的指导思想就是ITIL思想，带给大家的是可用性管理、发布管理、配置管理、变更管理，事件管理。

接触ITIL久了以后，用ITIL指导事件会发现一些问题：
- ITIL的这些理念非常正确，它总结得非常到位，好象已经无可再提炼了，但是要把这些指导思想从思想层面落地，好象中间有一点对不上，原因是什么呢？ITIL这些理念提炼得非常抽象，已经非常理论化了，如果我们再把它反推回去让它变成落地的实践是有点困难的。当然，ITIL里面已经提供了最佳实践，实施标准比如ISO20000之类的，但是热度不那么火，推广范围也没有那么广。所以，IT作为一个思想去指导我们怎么思考、怎么规划是非常有用的，但是真正要落地的时候，可能就有点困难。

- ITIL的制定已经有非常悠久的历史，ITIL是英国在80年代末开始制定的，在2000年成为国际标准。那个时候互联网应用并不发达，ITIL的很多指导思想是基于IT服务的，当我们把它应用到互联网运维领域的时候，总是感觉方向上是正确的，落地的时候好像缺一点点，这也是造成ITIL在我们互联网领域落地有点困难的原因。

基于以上两个原因，需要有一套基于ITIL思想同时又结合互联网应用领域实际落地经验的指导思想，来帮助大家怎么样更好地把互联网运维做好。

## 5. 互联网应用标准的体系构成
这套体系应该包括以下几个部分：

![](http://7xl5e0.com1.z0.glb.clouddn.com/C10004.png)

图片地址：http://7xl5e0.com1.z0.glb.clouddn.com/C10004.png

- 互联网应用运维框架。主要是作为一套指导思想，去告诉大家互联网应用运维需要做哪些大方向的事情；
- 互联网应用运维能力模型。这个运维能力模型是支撑这套框架的，同时也是一套对于运维能力的评估标准。
- 互联网应用运维规范。这个规范就是真正去指导如何落地，是能力模型和框架落地的主要部分。
- 互联网行业千变万化，虽然可以简单地把互联网行业的应用划分为游戏、社交、电商等等几大类，但是每个公司的情况各有不同，因此还需要沉淀各个不同行业的最佳实践案例，以此来指导每一个行业、每一个公司面对不同情况的时候，你可以去参考这些最佳实践案例，比如电商行业、通信行业、金融行业等等。

## 6. 互联网应用运维标准框架
应用运维存在的最大价值就是服务业务，这样我们的工作也应该围绕着业务来开展。一个典型互联网业务的链条包括从研发到上线，上线之后聚集用户、营销，后面还有下线等。

它分为研发期和运营期两大周期，应用运维主要工作聚集在运营期中，但是在研发期中也有应用运维要做的事情。

互联网应用运维框架就是基于整个业务的时间线来设计的。当一个业务应用在研发期的时间，这时候产品和研发是研发人员的主要工作，但是应用运维也可以做高可用架构设计，我们从运维经验中沉淀下来的高可用性方案输出给研发，研发在研发周期中就把业务的架构设计得更合理。所以，应用运维的框架中就有这样一个高可用架构设计在这里。

![](http://7xl5e0.com1.z0.glb.clouddn.com/C1%200005.png)

图片地址：http://7xl5e0.com1.z0.glb.clouddn.com/C10005.png

当业务上线的时候，持续部署是应用运维另外一个重要的工作。部署完之后还是不够的，业务可能出现故障，要及时发现和处理，这个时候就要做可用性保障，包括备份、监控等等。

业务的下一个阶段是要拉用户，我们这个时候要帮助业务更好地吸引用户，我们要提供一些数据给到业务，可能业务需要看一些在线的运营数据、用户数据，就需要我们运维提供和搜集，同时我们自己也需要在运维中发现我们系统的问题，比如有没有BUG，有没有用户体验的问题。

一个应用在整个运营周期中，其实会碰到很多用户体验上的问题，比如用户用得不爽会流失，这个时候我们要做什么？我们要做用户体验优化，通过应用运维不断地发现运营过程中的用户体验问题，找到问题点，持续推动改进，让我们的应用可以使用户用得更爽，这样用户更愿意留在我们的应用中。

在运营过程中可能还有很多大的活动，比如电商的双11，所以还要有专项运营活动的支持。

同时，成本也是运维可以帮助业务做的很大价值的事情，在整个周期中都有有持续成本优化的职责。

最后，客户服务，它不一定是运维直接面对我们的最终用户服务，这个客户服务是应用运维所面临的内部客户和外部客户，我们怎么样和他们建立良好的关系，怎么和他们之间有更好的信息沟通。

## 7. 互联网应用运维能力成熟度模型
我们把框架进行展开，对框架里的每一个点，每一个点哪些能力维度，通过五个层级的方式评估这些能力维度中做得怎么样，这就是能力模型。

![](http://7xl5e0.com1.z0.glb.clouddn.com/C10006.png)

图片地址：http://7xl5e0.com1.z0.glb.clouddn.com/C10006.png

进一步把这些能力模型再展开，看看每一级中去给大家一些指导的思路，怎么样把这个能力模型从一级到五级逐步提升起来。

比如数据服务中，数据项管理从1级到4级怎么做等等，这些都有详细的描述。
应用运维工作组经过半年的努力，现在已经把应用运维框架的草案拿出来了，我们把人力模型的草案也输出了，我们把这些草案都开源出来，开放出来，让大家都能够阅读，一起来建设。

![](http://7xl5e0.com1.z0.glb.clouddn.com/C10007.png)

图片地址：http://7xl5e0.com1.z0.glb.clouddn.com/C10007.png

同时，我们很希望这些最佳实践案例能够大家一起来贡献，因为凭我们自己的力量没有办法把最佳实践案例都收集齐，大家一起把整个模型、框架、案例完善起来。

所以，后面希望更多的人和应用运维工作组一起，把应用运维建设成第一套可以实际落地指导运维工作的一套规范体系，大家一起把它建设得更加完善。谢谢大家！

![](http://7xl5e0.com1.z0.glb.clouddn.com/C10008.png)

图片地址：http://7xl5e0.com1.z0.glb.clouddn.com/C10008.png

## 8. 标准的行业价值和意义
互联网应用运维框架及能力成熟度模型（本文）是我国仍至全世界第一个应用运维标准草案，其出现的意义重大，包括：

- 总结国内外大中型互联网企业的先进运维经验，减少中小型互联网企业的重复建设；
- 将互联网应用运维经验标准化，输出给传统企业，给传统企业互联网转型作为参考和指导；
- 将运维是从繁杂的技术工作中解脱出来，提升运维对企业的贡献，协助运维成为企业的核心竞争力之一。

## 9. 标准的推广
互联网应用运维草案目前已经编辑就绪，目前的推广计划为：

- 内测。限量邀请国内外资深运维从业者进行内部修正；
- 宣讲。组织各种线上和线下沙龙，综合各方修改意见，进行宣传和完成；
- 开源。发布本标准，并基于知识共享协议予以，允许更多的传播与修正。

## 10. 声明
本文编写过程中参考了国内外相关书籍，如有冒犯还请指出。
本文基于CC BY-NC-ND 3.0协议。
















