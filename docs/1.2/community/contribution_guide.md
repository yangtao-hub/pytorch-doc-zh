# PyTorch贡献指南

PyTorch是GPU加速的Python张量计算包大楼建成基于磁带的系统autograd深层神经网络。

## 所述PyTorch贡献过程

该PyTorch组织由[ PyTorch治理管辖[HTG1。](/docs/stable/community/governance.html)

该PyTorch开发过程中涉及的核心开发团队和社区之间公开讨论的一个健康的量。

PyTorch操作类似于GitHub上大多数开源项目。但是，如果你从来没有促成一个开源项目，下面是基本的过程。

  * **找出你要什么去努力。** 大多数的开源贡献来自让人摸不着自己的痒处。但是，如果你不知道你想要什么工作，或者只是希望获得与该项目有更多的了解，这里有一些提示，了解如何找到适当的任务：

    * 通览[问题跟踪](https://github.com/pytorch/pytorch/issues/)，看看是否有您知道如何解决任何问题。由其他贡献者确认的问题往往是更好地进行调查。我们也维持其很可能是好的，为新人们，例如问题的一些标签， **集训** 和 **1小时** ，尽管这些标签不太良好的维护。

    * 加入我们的时差，让我们知道你有兴趣去了解PyTorch。我们很高兴提供帮助研究人员和合作伙伴获得了代码库，以加快。

  * **找出你的变化范围，在GitHub的问题达成了设计的意见，如果是大的。** 大多数引入请求的小;在这种情况下，没有必要让我们知道你想要做什么，只是让开裂。但是，如果改变将是大的，它通常是一个好主意，先了解一下它的一些设计意见。

    * 如果你不知道变化有多大将是，我们可以帮你看着办吧！只是张贴关于它的问题或懈怠。

    * 一些新增功能是非常标准化的;例如，很多人添加新的运营商或优化，以PyTorch。在这些情况下设计的讨论主要是归结，“难道我们希望这个运营商/优化？”给了其效用，例如，使用在同行评审的论文，或存在其他框架的证据，使这种情况下，当有助于一点。 - **加法运算符/从最近发布的研究算法**

>
一般是不会接受的，除非有大量证据表明，这个新出版的作品有突破性的成果，并最终成为该领域的标准。如果你不知道从哪里你的方法跌倒，首先实施PR之前打开的问题。

    * 核心变化和refactors可以说是相当难以协调，为发展对PyTorch主步伐也相当快。当然伸手根本性或跨领域的变化;我们经常可以提供有关如何上演这样的变化成更容易审查的作品的指导。

  * **代码吧！**

    * 请参阅建议的技术导则技术形态与PyTorch工作。

  * **打开拉入请求。**

    * 如果你还没有准备好拉入请求进行审查，以[WIP]标记它。当这样做评审通过，我们将忽略它。如果你是在一个复杂的变化工作，这是很好的开始做事了作为WIP，因为你将需要花时间看CI结果看，如果事情成功的与否。

    * 找到适合您的变化适当的评审。我们有一些人谁经常通过公关排队去尝试，审查一切，但是如果你碰巧知道受你的补丁给定子系统的维护者是谁，随时直接包括他们拉入请求。您可以了解更多有关此结构在PyTorch子系统所有权。

  * 直到它接受了拉入请求 **迭代！**

    * 我们会尽最大努力减少审核往返，只有当有重大事项块永久居民的人数。对于引入请求的最常见的问题，看看常见误区[HTG1。

    * 一旦拉请求被接受和CI在流逝，没有什么别的你需要做的;我们将合并PR为您服务。

## 入门

### 提出新的功能

新功能的想法是对具体问题的最佳讨论。请包括你可以尽可能多的信息，相关的数据，和您的建议的解决方案。该PyTorch团队和社区经常回顾了新的问题和意见，他们认为他们可以提供帮助。如果您在您的解决方案有信心，继续前进，实现它。

### 报告问题

如果您已经通过在回购现有的问题中的[列表中标识的问题，第一个搜索。如果你无法找到一个类似的问题，然后创建一个新的。供应尽可能多的信息，你可以重现问题的行为。此外，包括像你期望的行为的任何额外的见解。](https://github.com/pytorch/pytorch/issues)

### 实施特色或修复错误

如果你想解决一个具体问题，最好与你的意图个别问题发表评论。但是，我们不锁或分配，除了在我们与开发商合作过案件的问题。这是最好的搭讪上的问题，并讨论你提出的解决方案。该PyTorch团队可以提供为您节省时间的指导。

被标记的第一新问题，低或中等优先问题提供最佳的介入点是伟大的地方开始。

### 添加教程

教程对[
pytorch.org了大量](http://pytorch.org/)来自社区本身，我们欢迎更多的捐款。要了解更多关于如何贡献新的教程，你可以在这里了解更多：[在Github上PyTorch.org教程贡献指南](https://github.com/pytorch/tutorials/#contributing)

### 提高文件&安培;教程

我们的目标是生产出高品质的文档和教程。在极少数情况下的内容包括错别字或错误。如果你发现了一些可以修复，给我们考虑拉入请求。

看看在文档部分，以了解我们的系统是如何工作的。

### 参与网上讨论

你可以找到积极的讨论发生在PyTorch讨论[论坛[HTG1。](https://discuss.pytorch.org/)

### 提交引入请求解决悬而未决的问题

您可以查看所有打开的问题[此处](https://github.com/pytorch/pytorch/issues)列表。在谈到一个问题，是一个伟大的方式来获得球队的关注。从这里你可以分享你的想法和你打算如何解决这个问题。

更具挑战性的问题，该小组将提供如何最好地解决这一问题的反馈和方向。

如果你不能够解决的问题本身，评论和分享您是否可以重现该问题可以帮助球队找出问题所在有用。

### 回顾开放引入请求

我们感谢您的帮助审查和评论引入请求。我们的团队努力保持开放引入请求的数量在可管理的范围，我们迅速作出反应的详细信息，如果我们需要它，我们合并，我们认为是有用的永久居民。然而，由于高度的兴趣，对引入请求额外的眼睛是赞赏。

### 改进代码可读性

提高代码的可读性可以帮助大家。它往往是更好地提交的少数几个触摸与文件触及许多文件大拉的请求拉请求。开始在PyTorch论坛[此处](https://discuss.pytorch.org/)或与您的改进问题的讨论是开始的最好方式。

### 添加测试用例，使代码库更加健壮

附加的测试覆盖率理解。

### 促进PyTorch

你在你的项目中，研究论文，使用PyTorch的写起坐，博客或一般性讨论在互联网有助于提高意识，为PyTorch和我们成长的社区。请联络[ pytorch-
marketing@fb.com [HTG1对于营销支持。](http://mailto:pytorch-marketing@fb.com/)

### 检伤分类问题

如果你觉得一个问题可以从有关这一问题的特定标签或复杂的注释水平中受益，分享你的意见。如果你觉得一个问题是未分类的正确意见，并让球队知道。

## 关于开源开发

如果这是您第一次贡献一个开源项目，开发过程中的某些方面可能看起来不寻常的给你。

  * **有没有办法“要求”的问题。** 人们经常想“要求”时，他们决定进行这项工作，以确保当别人结束了它的工作有没有浪费工作的问题。这并没有真正的开源工作也很好，因为有人可以决定的东西的工作，并最终没有时间去做。可以随意的信息咨询的方式，但在这一天结束时，我们将采取运行的代码，并大体一致。

  * [HTG0存在对于被添加新功能的高杆。 [HTG1不像在企业环境中，谁写代码的人含蓄地“拥有”，并可以预计到，立即照顾它在其生命周期的开始，一次拉请求被合并成一个开源项目，它成为该项目的所有维护人员的集体责任。当我们合并代码中，我们说我们的维护人员，都能够审查的后续变化，并作出修正错误的代码。这自然导致了更高的标准贡献。

## 常见的错误，以避免

  * **你添加的测试？** (或者如果改变是很难测试，你描述你如何测试你的改变？）

    * 我们有我们为什么要求测试的几个动机：

      1. 帮助我们告诉我们，如果以后打破它

      2. 帮助我们告诉我们，如果补丁是在第一时间正确的(是的，我们没有审查，但克努特说，“当心下面的代码，因为我还没有运行它，只是证明了它正确”）

    * 什么时候确定不添加测试？有时变化不能方便地进行测试，或者改变是如此明显正确的(且不太可能被打破），它是确定不进行测试。相反，如果一个变化很可能(或者被称为是有可能的）被意外打破，它把在制定测试策略的时间是非常重要的。

  * **是你的PR过长？**

    * 这是我们更容易查看和合并小的PR。回顾公关的难度与它的大小尺度非线性。

    * 什么时候确定，提交了大量公关？它有很大帮助，如果有中的问题相应的设计讨论，与谁是要检查您的DIFF人签署。我们还可以帮助提供有关如何拆分大的变化成单独可交付的部分建议。同样，它帮助，如果还有的公关内容的完整描述：它更容易检查的代码，如果我们知道里面是什么！

  * **评论对微妙的东西？ [HTG1在情况下，你的代码的行为是细致入微，请包括额外的注释和文档，使我们能够更好地理解你的代码的意图。**

  * **你添加一个黑客？** 有时，一个黑客是正确的答案。但通常，我们将要讨论它。

  * **你要摸一个非常核心的组成部分？ [HTG1为了防止大回归，拉那一抹核心组件的请求获得额外的审查。请确保你在进行重大变化之前已经讨论过的团队所做的更改。**

  * **要添加新的功能？ [HTG1如果要添加新的功能，对相关问题发表评论你的意图。我们的团队试图发表评论，并提供反馈给社会。这是更好地之前建立新的功能与团队和社会的其他开放式讨论。这有助于我们保持知道你的工作是什么对和增加了它会被合并的机会。**

  * **你触摸无关的代码的公关？** 为了在代码审查帮助，请只在您的拉请求直接相关的更改文件。

经常问的问题

  * **如何作为一个评论家贡献？** 有很多的价值，如果小区的开发商重现问题，尝试新的功能，或以其他方式帮助我们确定或解决问题。在谈到与环境信息的任务或引入请求是有帮助和赞赏。

  * **CI测试失败了，这是什么意思？** 也许你需要与主合并或与最新的变化变基。推你的变化应该重新触发CI测试。如果测试持续下去，你会希望通过错误信息来跟踪和解决相关问题。

  * **什么是最高危的变化？** 凡是触摸构建配置是一个有风险的区域。请避免改变这些，除非你已经与球队讨论事前。

  * **嘿，提交我的分支出现了，那是什么回事？** 有时其他社区成员会提供修补程序或补丁，以您的拉请求或分公司。这通常需要获得CI测试通过。

## 在文档

### Python文档

PyTorch文档从蟒源使用[斯芬克斯](http://www.sphinx-
doc.org/en/master/)生成。生成的HTML被复制到文档文件夹中的[ pytorch.github.io
](https://github.com/pytorch/pytorch.github.io/tree/master/docs)主分支，并且经由GitHub的页供应。

  * 网站：http://pytorch.org/docs 

  * GitHub的：[ https://github.com/pytorch/pytorch/tree/master/docs ](https://github.com/pytorch/pytorch/tree/master/docs)

  * 从供应：[ https://github.com/pytorch/pytorch.github.io/tree/master/doc ](https://github.com/pytorch/pytorch.github.io/tree/master/docs)

### C ++文档

对于C ++代码，我们使用的Doxygen生成内容的文件。 C ++的文档都建有专门的服务器上生成的文件复制到[
https://github.com/pytorch/cppdocs
](https://github.com/pytorch/cppdocs)回购，并从GitHub页面服务。

  * 网站：http://pytorch.org/cppdocs 

  * GitHub的：[ https://github.com/pytorch/pytorch/tree/master/docs/cpp ](https://github.com/pytorch/pytorch/tree/master/docs/cpp)

  * 从供应：[ https://github.com/pytorch/cppdocs ](https://github.com/pytorch/cppdocs)

## 教程

PyTorch教程是用于帮助了解使用PyTorch完成特定任务或要了解更全面的概念文件。教程使用[狮身人面像，画廊](https://sphinx-
gallery.readthedocs.io/en/latest/index.html)从Python可执行文件的来源，或重组文本(RST）文件建立。

  * 网站：http://pytorch.org/tutorials 

  * GitHub的：[ http://github.com/pytorch/tutorials ](http://github.com/pytorch/tutorials)

### 教程构建概述HTG0]

对于教程[拉请求](https://github.com/pytorch/tutorials/pulls)触发使用CircleCI测试变化的影响，重建整个网站。此版本是分片到9个工作建立和总花费约40分钟。与此同时，我们做了Netlify建立使用
_让HTML的noplot_ ，它建立了网站，而无需渲染笔记本输出到快速审核页面。

一个PR被接受后，该网站是重建和CircleCI部署。

### 贡献新的教程

[ PyTorch.org教程贡献指南](https://github.com/pytorch/tutorials/#contributing)

[Next ![](../_static/images/chevron-right-orange.svg)](governance.html
"PyTorch Governance") [![](../_static/images/chevron-right-orange.svg)
Previous](../notes/windows.html "Windows FAQ")

* * *

©版权所有2019年，Torch 贡献者。
