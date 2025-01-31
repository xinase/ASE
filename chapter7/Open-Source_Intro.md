开源软件开发导论 - 第一章

## 开源教学的挑战
我们这个课程的目的，是要向学生介绍：

1）开源是什么（what）

2）为何有开源 （why），开源是如何发展到今天的状态的 （how）

3）作为 IT 专业人士，我们应该如何利用开源来实现我们的目的（what - how）

开源：开源是将源代码、设计文档或其他创作内容开放共享的一技术开发和发行模式。 在开源模式下，通过许可证的方式，使用者在遵守许可限制的条件下，可以自由获取源代码和其他资料，并可以使用，复制，修改和再发布。 开源模式是一种依托互联网平台，大规模群体智慧通过共同参与与协作而不断累积，实现持续创新的方法。 在开源模式中，项目的核心开发人员与大规模的外围群体紧密合作，他们通过互联网共享资源、开展协同开发、管理代码等，由此使得项目开发的效率、应对需求变化的能力大大提升。  （2022 中国开源发展白皮书）

开源的实践利用到了：软件工程学、管理学、社会学、经济学和法律学等知识。 

开源活动的参与者在各种 ”开源社区“ 中活动，不同的角色从这个”社区“ 想达到的目的是不一样的。 

参与开源的技术工程人员：利用开源社区学习，解决问题，发布宣传产品，让自己获益。 

参与开源的企业：专注于如何让企业从开源社区中获得短期和长期的利益，关注开源的安全合规，以及和企业治理相关的问题。 

开源平台的构建和维护者：如何为各种角色服务，让开源生态在自己的平台得到可控的良性发展，实现平台的商业和非商业目标。 

参与开源的研究者：研究开源的各个角色在数字空间中大规模协作背后的规律，进而为社区治理与运营提供指导。 

#### 开源的领域知识
开源的领域知识具有非常强的实践性，需要亲身实践才能体会和掌握（就像游泳一样）。 开源的领域知识的不少部分都是属于 “暗默知识 （tacit knowledge）”，它们源于个人的亲身体验，是与个人信念、视角、和价值观等精神层面密切相关，是一种 “行动中的知识”。 很多概念和原则，是要通过亲身体验，反复行动才能深刻理解的。 

学习了这门课，有了一定的开源的领域知识和实践的经历，你获得了什么？ 

1）证明你有一定的专业知识，可以在开源社区工作。

2）证明你能和许多不同特点的人一起合作达到一个目标。 这说明你具备一定的 “沟通管理” 的实战技能。 

3）你在开源社区的贡献，是你简历和声望的重要部分，它们为你将来的工业界和学术界的发展奠定了很好的基础。 

4）为你在开源领域做学术研究做了一些初始的准备。 

### 迎接开源教学的挑战

1）教学内容尽量开源，用开源社区最常用方式 -- MarkDown 文档。 

2）教学和实践紧密结合 - 大家可以在这个课程用开源的方式来实现一些开源产品的功能，有偏代码方面的，也有偏领域知识整理方面的。 作业的提交和讨论尽可能地用公开的方式进行。 

3）和工业界紧密结合 - 我们会邀请工业界优秀的初创企业来分享他们的开源实践，他们也会提供实习的机会。 同学们在本课程就可以进行实习。 

同学们，开始实践吧！

## 开源的发展历史
（1）通过对比闭源软件，介绍开源软件基本概念、发展历史、国外开源软件发展现状（1学时）；

| 年代   | 环境/文化                                                                                                                                                                                                                                                                                   | 计算机/OS                                                                                                                                                                                                      | 应用软件                                                                                                                    | 版权                                                                                                                                                                                                                                                                                                                                                                         |
|------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1950 | 随着 ENIAC 的成功，程序员意识到编程不仅仅是一门挣钱的工作，还是一件有更大意义的事情，值得怀着热情去探索和发扬光大。 <br/>  Grace Hopper sharing compiler source code                                                                                                                                                                          | OS 是为计算机定制的，只有简单的功能                                                                                                                                                                                         | .                                                                                                                       | .                                                                                                                                                                                                                                                                                                                                                                          |
| 1960 | 黑客（hacker）文化兴起： 分享所有信息，鼓励探索，不喜欢权威，秘密，理性分析。Playful cleverness。  <br/>早期：分享代码是科学家和工程师的常见合作方式                                                                                                                                                                                              | 1969 Unix 早期版本出现                                                                                                                                                                                            | .                                                                                                                       | .                                                                                                                                                                                                                                                                                                                                                                          |
| 1970 | 1975: 计算机爱好者在一个硅谷的车库聚会，开始 Homebrew Computer Club，分享编程和计算机信息和演示.  <br/> 七十年代末，John Lions 注释并分享了 Unix 6th Edition 的源代码，在全世界高校的计算机系中流传。 AT&T/贝尔实验室不允许这样的传播。                                                                                                                                                   | 1973: PC：PARC Alto <br/>1976: PC：Apple I <br/> 1978: 随着Unix 在大学传播和发展 ， UC Berkely 发布了它自己的 BSD 版本，导致了 Unix 版权争执 <br/>1979: Steve Jobs 和他的团队参观 PARC，看到了 Alto 电脑和其他先进技术。                                       | 1976:VI， Emacs                                                                                                          | 1975: Bill Gates 和 Paul Allen 签约给 MITS 开发 BASIC 语言解释器， 每份卖出的拷贝收 30 - 60美元。  <br/> 1975: Palo Alto 的计算机爱好者获得了一份未发布的 Basic 解释器源代码并分享给俱乐部成员。 别的公司开始制造 MITS 兼容的内存卡并 “赠送” BASIC 解释器软件。  <br/> 1976: Bill Gates 给计算机爱好者的公开信，呼吁停止盗版软件。                                                                                                                                            |
| 1980 | .                                                                                                                                                                                                                                                                                       | 1981: DOS 诞生（IBM + Microsoft). <br/> 1983 - 1984: Apple Lisa， Macintosh 发布. <br/>1985: Windows 1.0 发布. <br/>1987: MINIX:  类似 Unix 的教学 OS, 为 IBM/PC架构开发， Andrew Tanenbaum, 源代码公开，为了教学的目的。3 个月内有 4万名用户订阅了 comp.os.minix <br/> 1988: David Culter 开始设计 Windows NT  | 1989 年底，Guido van Rossum 决定开发一个新的语言 Python，作为假期的小项目。                                                                                                                         | 1981: BM 不想拥有 OS 的版权，不想让自己的开发人员看到 OS 代码。   <br/> 1982: Shareware 使用协议出现 <br/> 1983: Richard Stallman 开始了 GNU 项目，要打造一个 “自由的” 操作系统，他还创立了 GNU General Public License (GPL).  <br/> 1985: Microsft 建议 Apple 把 Mac OS 开放给其它制造商，Apple 拒绝了。 Microsoft 开始全力打造自己的 Windows OS，同时，Microsoft 和 Apple 签协议可以使用部分 UI 设计。  <br/> 1988: Apple 控告 Microsoft 在 Windows 2.0 中抄袭了 Mac 的 UI 设计。  |
| 1990 | 1998/4/7: O'Reily 主持了第一个 OpenSource Summit                                                                                                                                                                                                                                              | 1991： 芬兰大学生 Linus Torvalds 在给 MINIX 做贡献后，说他想写一个独立的类似 Unix 的操作系统，作为业余爱好。<br/>   1993：100 个开发人员在开发 Linux Kernel.  <br/> 1994： Linux 1.0 发布，SUSE, RedHat 成为商用发行商。                                                               | 1994: comp.lang.python 讨论组成立，标志 Python 这个开源的语言得到很多主流用户的认可 <br/> 1995: MySQL 发布 <br/> 1995: Apache HTTP server 发布 <br/> 1995: PHP 发布                                                     | Linux 采用了 GPL                                                                                                                                                                                                                                                                                                                                                              |
| 2000 | 互联网极大发展，高端：Sun 的工作站，Cisco 的网络设备，EMC 的存储，Oracle 的数据库。<br/>   低端：LAMP： Linux， Apache 网站服务器，MySQL 数据，PHP 脚本语言。 <br/>  企业 IT 服务： scale-up. 买越来越高级的专用服务器 和商用软件 转向 scale-out: 用便宜的硬件和软件取代. <br/> 企业 IT 战略： build or buy?  购买专用服务（被锁定） vs 自己构建 （技术和人力成本）。<br/> 原来只能二选一，现在 开源可以有一个混合模型，满足企业需要。  | 2001: Apple 开始开发 Unix-based 的MacOS   2003: IBM 宣布把 Linux 作为它战略的重要部分。 开源是和“互联网”同样重要的战略。  <br/> 2008: 开源的 Android OS 发布                                                                                       | 2000: StarOffice 变成开源和免费的软件 <br/> 2002: FireFox 浏览器发布 <br/> 2005: Git 发布 <br/> 2008: Chrome 浏览器发布 <br/> 2008: GitHub 发布 | .                                                                                                                                                                                                                                                                                                                                                                          |
| 2010 | 2013: 去IOE 在阿里公司完成，IBM 小型机，Oracle 数据库，EMC 的高端 SAN 存储，用开源产品取代                                                                                                                                                                                                                            | 2011: Chrome OS 发布                                                                                                                                                                                          | 2014: VUE.js 发布                                                                                                         | 2015: MIT license 成为 GitHub 上最流行的许可证                                                                                                                                                                                                                                                                                                                                       |
| 2020 | 2020: 95% 的企业说 开源软件是他们企业 IT 基础建设的重要部分。                                                                                                                                                                                                                                                  | .                                                                                                                                                                                                           | .                                                                                                                       | .                                                                                                                                                                                                                                                                                                                                                                          |

### 开源发展历史的脉络
注：关于开源的历史，在网络有很多介绍，我（邹欣）在这里不想做其他文档的复读机，而是主要讲我的理解。 由于我的水平、经历和看问题的角度，我的看法可能有不准确，不符合事实，或者有偏颇之处，希望大家指出这些问题，我们可以展开进一步的讨论和澄清。 

1. 1940 - 1950 年代: 开拓阶段

计算机科学的发展，是建立在其他学科的基础上的，自然地，计算机软件的发展也不例外。 

在计算机发展的早期（1940 年代），它的硬件有非常有限的速度和容量。 
Mark I：CPU 内部计算一个加法：300 毫秒； 相当于 3 Hz 的主频。 大家手里的笔记本电脑是 1G Hz 主频。 
Mark I 的内存：
72 storag registers, each holds 2 23-digit decimal numbers and its algegraic sign. 

程序员的工作：把一个计算公式（例如 一个复杂的方程）转化为 --> 数字和数字的操作 --> 输入到电脑中。 直接使用机器语言 （汇编语言）

早期的程序就是把数学公式变为一个计算机能执行的对数据操作的序列。 

早期的程序员都是搞数学的，每一段汇编代码是和机器的细节，包括内存的地址绑定的，程序无法重用到另一次的执行中（因为内存地址不一样了），而不用说，程序能够分享到别的机器上了。 在1945 年， Mark I 的程序员开发了很多常用的数学公式的实现方法，但是在拷贝代码的时候，要把地址重新安排，很不方便。 这些方法如何能够方便地让大家互相使用呢？ 一个想法，从原来的直接使用机器的绝对地址变为 “relative coding"，建立了一个抽象 --- 不实用绝对的地址，而是使用相对的地址。 


1946 年 5 月: John von Neumann 发表了 “First Draft of a Report on the EDVAC", 描述了现代计算机的结构：
- binary logic gates
- stored instructions and data
- serial execution of instructions

怎么实现 “stored instructions / programs", 而不被具体的机器细节所绑定？ 如何用参数来支持对这个program 对不同输入？ 这就是 sub-routine （子程序）的产生。 

1950: Mark III 电脑诞生，支持 subroutine 的功能，让 “子程序” 可以方便地在不同的地方被调用。 

Grace Hopper 霍珀在工作中，对于早期计算机指令的规范也做出了很多贡献。
 
在计算机出现的早期，指令都是用二进制或者八进制来表示的。机器只认识这些数字，对于机器来说，挺方便的。但计算机代码，究竟是给计算机读的，还是给人读的呢？
 
霍珀和其他程序员在实践中发现，这些代码需要花很多时间来记忆，修改，和讨论，执行起来很不方便，于是他们做了一系列的改进：
首先，用英语字母来表示计算机指令，这样程序员就能方便地阅读和理解。
其次，霍珀成了第一个在源程序上写注释的程序员，这个习惯传到了很多其他人。

第三，她们发明了流程图 （Flow Chart），使用矩形来代表操作，使用菱形来代表选择。俗话说“一图胜千言”，流程图极大地提升了工作效率。所以一直到 70多年后的今天，还会被许多初学者沿用，帮助设计和理解程序。  
 
在1950 年代末，沿着 "让计算机程序容易写，容易理解”的思路，霍珀还领导设计了现代编程语言 COBOL，这个语言后面被广泛地用于商业领域。
同时，沿着 "更高效地做科学计算“ 的思路， 为了 Formula Tranlating  而设计，诞生了 FORTRAN，当时的 IBM 电脑只有大写英语字母，因此这个语言的字母也全部大写，后来才改为 Fortran。 （早期发明者：John Backus 1953 - 1957）

随着计算机在二战后从科学计算转移到了商业应用，软件工程师开始考虑 “商业利益”， “知识产权” 的问题。 

1950 年代， Hopper 主持了 Compiler 的研究，把高级语言编译为针对各个不同电脑的汇编代码，在这个过程中，她坚持了 “源代码共享”： 

The fact that Hopper wholeheartedly welcomed non- UNIVAC personnel to learn about the A-2 compiler sheds some light on her beliefs concerning intellectual property. Hopper did not view software as a commodity to be patented and sold. Rather, she took her cue from the mathematics community. Like most other academics, mathematicians shared information universally, in order to advance knowledge. Though individual efforts were acknowledged by colleagues, advancement in the field was contingent on a communal view of information, community validation, and evolutionary advancement based on previous work. In the same way, software, according to Hopper, was a public good to be shared freely among all users. Complicating software development with secrecy would only inhibit innovation.

Beyer, Kurt W.. Grace Hopper and the Invention of the Information Age (Lemelson Center Studies in Invention and Innovation series Book 4) .




总结：在早期的计算机上，“软件” 只是实现把数学公式转化到机器代码中，子程序的出现，让大多数的常用计算公式能够一次写好，多次被调用。随着计算机软件科学和技术的发展，如何分享 “科研成果” vs “保护商业利益” 成为程序员需要面对的问题。 

2. 1960 - 1970 年代： 
在环境/文化方面： 黑客文化兴起 （请看 Ken Thompson 的故事）
在计算机/OS 方面： Unix 在大学计算机教育界的兴起和版权纠纷
在应用软件方面：VI，Emacs：
商业创新方面： 个人电脑：Xerox Parc 的 Alto 电脑， Apple I，BASIC 解释器
软件许可证的诞生： EULA： End User License Agreement. 

3. 1980 - 1990 年代： 开源的商业萌芽
商业版权： 导致 Unix 的碎片化， 导致商业发展的停滞和版权纠纷。 Macintosh, DOS, Windows, Windows NT, OS/2 ...
自发的开源项目从萌芽阶段发展： MINIX， Linux 等开源 OS 等产生。 MySQL， Apache，PHP。 
"Talk is cheap. Show me the code."     - Linus Torvalds
技术极客（geek）更专注于软件创新的核心：源代码。 

----
Linus Torvalds 的 comp.os.minix 讨论帖子：
1991/8/25:
Hello everybody out there using minix -

I'm doing a (free) operating system (just a hobby, won't be big and professional like gnu) for 386(486) AT clones. This has been brewing since april, and is starting to get ready. I'd like any feedback on things people like/dislike in minix, as my OS resembles it somewhat (same physical layout of the file-system (due to practical reasons) among other things).

I've currently ported bash(1.08) and gcc(1.40), and things seem to work. This implies that I'll get something practical within a few months, and I'd like to know what features most people would want. Any suggestions are welcome, but I won't promise I'll implement them :-)

Linus (torvalds@kruuna.helsinki.fi)

PS. Yes - it's free of any minix code, and it has a multi-threaded fs. It is NOT portable (uses 386 task switching etc), and it probably never will support anything other than AT-harddisks, as that's all I have :-(.

— Linus Torvalds
----



4. 2000 - now 高速发展阶段
几乎所有的软件都有开源的替代产品。 

互联网技术和产业的几次潮起潮落让开源成为一个实用而可以操作的选择。 
高端：Sun 的工作站，Cisco 的网络设备，EMC 的存储，Oracle 的数据库。    （硬件+软件费用轻易就能达到 百万美元/年）
低端：LAMP： Linux， Apache 网站服务器，MySQL 数据，PHP 脚本语言。    （软件是免费的）
企业 IT 服务： scale-up. 买越来越高级的专用服务器和商用软件 转向 scale-out: 用便宜的硬件和软件取代.  
企业 IT 战略： build or buy?  购买专用服务（被锁定） vs 自己构建 （技术和人力成本）。 原来只能二选一，现在 开源可以有一个混合模型，满足企业需要。

2020: 95% 的企业说 开源软件是他们企业 IT 基础建设的重要部分。



### 国内开源的发展现状
（2）国内开源的发展现状, 参看 2022 中国开源发展蓝皮书。 

### 相关资料
开源，社区合作相关的书籍： https://github.com/oscar-open-source-book/booklet-2022 