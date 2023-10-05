# 零阶宇宙学误解辨析

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">零阶宇宙学误解辨析 (Notes on Confusions in the Zeroth-order Cosmology)</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/ycwang-hello/notes-on-cosmology" property="cc:attributionName" rel="cc:attributionURL">王彧辰 (Yu-Chen Wang)</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

## 前言 Preface

什么是“零阶宇宙学”？宇宙学关心的问题之一是宇宙的时空（或引力）性质（如尺度因子）和宇宙中各组分性质（如密度、压强等）随时间的演化。这不是一个简单的问题，因为宇宙有着复杂的结构，时空和各成分的性质是关于时间和空间的函数。要想研究这个问题，最好的办法是由简入繁，用微扰论的常见思路。我们知道，在足够大的尺度上，宇宙是均匀和各向同性的（宇宙学原理）；例如，如果我们把密度场用一个很大的半径做一个平滑，那么整个宇宙就是均匀的，（大尺度平滑后的）密度场不再是空间的函数，而只是时间的函数。在宇宙学原理的基础上，我们能够给出宇宙整体的演化；以它作为背景，我们把密度对平均密度的偏离作为在此基础上的扰动，于是就有了线性扰动的理论。如果说线性扰动是一阶项，那么宇宙整体均匀各向同性的背景就是零阶项。从这个意义上，这里把它称作是“零阶”宇宙学。

零阶宇宙学既是宇宙学的基础，也是整体天体物理学的基础。你可能不关心宇宙具体的结构形成，但你很可能对于宇宙整体的演化，和暴胀、奥伯斯佯谬等许多宇宙学中的现象感兴趣。对于研究星系和高红移宇宙的人，零阶宇宙学也是无法避开的问题，因为它是我们能说遥远天体的距离乃至其物理性质的基础。因此，零阶宇宙学在天文和物理学生/研究者中的普及程度，应该远高于更深入的宇宙学内容。本文的讨论范围就限于零阶宇宙学。

我在2016年第一次听说了零阶宇宙学中的部分概念，2018年第一次看到了零阶宇宙学的教材，2019年第一次正式学习零阶宇宙学，至今作为学生学习零阶宇宙学、作为零阶宇宙学课程的助教都已经有几次了。零阶宇宙学本科生就能学习，内容相对并不复杂（对于真搞宇宙学的人来说这可能太简单了），也比较吸引人。但是听过一次零阶宇宙学的课，或者看过教材，就真的学明白了吗？

作为多次接触零阶宇宙学教学的人，我认为未必。读者可尝试判断以下陈述的正误：
- 角直径距离是物理距离除以$(1+z)$，这是因为我们看到天体的大小其实是它的物理尺度除以它以前与我们的距离，而不是今天的距离（也就是今天的物理距离除以$(1+z)$）。
- 宇宙学红移是因为宇宙在膨胀，遥远的天体远离我们而产生了多普勒效应。
- 在膨胀的宇宙中，仍然有宇宙中总能量守恒。
- 我们可观测宇宙的大小称作哈勃半径，它是一个无限红移面。在哈勃半径之外物体的退行速度超光速了，所以这些我们看不到。
- 由于宇宙的加速膨胀，和我们能有因果联系的星系就会越来越少了。
- 之所以暴胀能解决视界疑难，是因为远处这两个点虽然现在没有因果联系，但是暴胀是宇宙把两点的距离剧烈拉大，其实这两个点在暴胀前距离非常近，它们当时是有因果联系的。而暴胀之后，它们被拉出了各自的视界范围，不再有联系（当然它们在过去或者将来可能还会重新进入各自的视界）。
- 根据奥伯斯佯谬，夜空会是无限亮。但是，实际上星际物质对于光会有吸收。而且宇宙在膨胀，光子会红移的，这就能解决了奥伯斯佯谬。另外，如果宇宙大小是有限的，那么我们也不会有奥伯斯佯谬的问题出现。

上面的所有陈述**全部错误**。遗憾的是，许多宇宙学入门的教材和其他资料中并未提及或强调这些内容；对于讲到这些内容的，有些讲法有着暗示读者产生上述误解的风险，甚至直接就有这些误解。

大部分情况下，凭基础课未必真的能学明白这些内容。本科生可以认为自己学会了本科课程，题目都会做，考试成绩可能也不错，但是学到的东西却未必经得起推敲和追问。越是深入地思考这些内容，像一个喜欢提出古怪问题的学生一样问自己，越可能发现更多的疑惑。从这个意义上，我多次的学习和教学经历给了我这样的条件，让我能够更认真地审视这些问题——即使你认为有些问题像是没学明白的人提出来的奇怪问题，如果你给不出满意的答复，说明其实是你根本没学明白。

在这样的经历中，我耗费了大量的精力重新审视这些看似简单的知识，也出现了大量的迷惑，而对这些迷惑和曾经犯过的错误的思考和整理也为我积累了大量的笔记。据不完全统计，我在各个地方积累下来和零阶宇宙学相关的笔记文件竟有8个之多！

于是，我希望把我积累的这些笔记重新整理成一个相对完整的文档，以期对其他同样对于零阶宇宙学感兴趣、在学习零阶宇宙学的读者有所帮助，这就有了你现在看到的这个文件。这份笔记主要以问题的形式组织，内容主要涵盖了角直径距离与光度距离、红移、视界、暴胀对大爆炸宇宙学疑难的解决和奥伯斯佯谬及其解决。笔记强调了作为初学者可能出现的错误和对部分概念的误解。为帮助尚不了解相对论中部分概念的读者，也为了声明本文采用的符号和名词系统，在第一部分首先重述了相对论的基本概念和宇宙的几何、动力学的一点概念。

整理笔记并不是一件容易的事。自己不同时期的笔记语言风格有所差异，符号和名词系统也未必完全相同。自己原始的思考是相对杂乱的，需要从中提取出关键的信息，以一种其他人也能读懂的方式重新组织。同时，也需要补充不少背景信息，因为读者未必完全记住了我写这些笔记时已经清楚的各项知识。为了更好地辅助文字描述，我还为这个笔记绘制了不少示意图。即便如此，我相信这篇笔记仍然没能做到最好。当我发现问题时，我会在未来的再版中修正。

虽然我尽可能降低阅读的门槛，但读者最好还是具有基本的大学物理和高等数学基础。个别话题可能涉及到一点分析力学、狭义相对论（在本科一般在普通物理力学和电动力学中介绍）和辐射度学的知识基础。本文不假设读者具有任何广义相对论的知识，但是学过少量广义相对论对于深入理解是有帮助的。部分需要有较多数学和相对论基础的内容放在了补充阅读中，这部分可以跳过而不影响整体理解。由于不是一个宇宙学讲义，我暂时没能做到不需要任何零阶宇宙学的基础，因此这笔记更加适合正在学习或者已经学过基础的宇宙学课程的读者。如果读者不了解宇宙学的背景知识，可以把本笔记和任何一本宇宙学入门/导论教材配合使用。

从我的第一份宇宙学笔记到这份《零阶宇宙学误解辨析》的发布，我已经积累了四年，但我仍然不能说真正理解了零阶宇宙学这些话题中可能涉及的全部问题。这篇笔记正文中的所有内容仅供你参考，你需要自行判断我写的笔记的正确性。**我无法保证正文中任何内容的正确性，对于这一笔记可能造成的任何损失均不负责**（本文许可协议第五条）！如果读者发现笔记中有错误，或者因缺乏背景、讲解问题等原因而无法读懂的内容，请及时与我联系（可在GitHub上提交[issue](https://github.com/ycwang-hello/notes-on-cosmology/issues)），我将不胜感激。

愿这份笔记能为在学习零阶宇宙学，或者对零阶宇宙学感兴趣的读者有所帮助。

