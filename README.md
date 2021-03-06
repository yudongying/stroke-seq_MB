笔顺数码输入法码表 stroke-seq_MB

    版权：GPL v3+
    遵照《GB13000.1字符集汉字字序（笔画序）规范》共20902个汉字
    遵照《GB13000.1字符集汉字笔顺规范》
    遵照2013年6月印发的《通用规范汉字表》8100个简体繁体异体字对照表
    参考《数字五笔中文输入系统输入教程及编码查询手册》并扩充添加规则
    基于专利权已终止的（CN03159505.7）一种数字笔画汉字输入方法
    原发明人：马晓光 <232937@QQ.com>
    开源码表手工录入：一善鱼 YQ-YSY <YQ-YSY@163.com>
    欢迎各位朋友利用此码表，或开发独立的笔顺输入法，或嵌入已开发的输入法。
    为了方便大家编辑并导出码表，在此附带原始的LibreOffice电子表格ods文件，里面有详细的分类和编号。
    
* * *
    
<big>按键说明</big>

    笔顺数码输入法使用键盘数字小键盘为主要输入工具，单手即可完成简体繁体文字、词组以及标点符号的输入。
    输入速度快，重码极少，适合编写长篇文章、会议速记等工作，符合华人书写习惯，避免“提笔忘字”的电脑病。
    小键盘的0~9按键默认是录入汉字，若先输入“*（星号）”紧接着输入0~9则为录入数字；
    按键“/（斜杠号）”单独输入时为逗号，
    按键“*（星号）”单独输入时为切换到数字输入模式，若跟随在编码后输入则作为未知编码的通配符；
    按键“-（减号）”为撤销上一步按键（类似BackSpace向左退格键）；
    按键“+（加号）”单独输入时为+号，若跟随在编码后输入则切换到候选字选词模式，继续输入0~9选择列出的字词；
    按键“Enter（回车）”用于确认选中排在第一个的候选字词就是需要的字词；
    按键“.（点号）”单独输入时为逗号，若跟随在编码后输入则作为词组的汉字间隔符；
    按键“00”为列出标点符号候选；按键“09）”为列出特殊序号候选。
    
    大键盘上的其它按键，与其它输入法功能相同。例如：
    -号或者 PageUp 候选字词向上翻页；=号或者PageDown 候选字词向下翻页；
    Shift 4 为￥人民币符号，Shift 6 为……省略号，shift < shuift > 为书名号《》等。
    为了方便没有数字小键盘的笔记本用户，建议输入法开发者提供自定义按键替换0~9的功能，以及繁体简体互换功能。
    
* * *
    
<big>一、基本输入方法（笔顺码）</big>

    以1、2、3、4、5五个数字分别代表“一丨丿丶乛”五个笔画，按汉字笔顺进行输入。其中：
    “提”归为“一”：如“氵、扌”中的最后一笔；
    “亅”归为“丨”：如“小”字的第一笔；
    “捺”归为“丶”：如“文、入、表”的最后一笔；
    各种折笔（乛、乚、、⺄、弯钩等）都归为“乛”：如“为、孔、民”中的笔画。

    例如：
    “开”字，按笔顺“一、一、丿、丨”，代码为1132；
    “我”字为31；“向”字为325；“力”为53；
    一般说来，常用字只需输1-4码。

    标点符号输入：
    常用标点符号可以输入“00”,常用的数字序号可以输入“09”。
    
* * *
    
<big> 二、部件输入方法（精简码）</big>

    利用"6、7、8、9、0"来代表部件笔画"横、竖、撇、点、折"，
    击下这些键后，将在输入框中显示出以该笔画起笔的8-10个常用部件，用户根据部件的序号击相应数字完成部件输入。
    5个笔画引出的常用部件及序号如下（共48个）：
    
    61 王    62 木（朩）    63 石    64 艹    65 车（車）    66 扌    67 土（士走）    68 酉    69 雨    60 廿（革）
    71 日    72 目    73 山    74 田    75 口    76 ⻊（足）    77 虫    78 贝（貝）    79 罒（四皿）    70 巾
    81 钅（釒金）    82 亻    83 禾    84 人（飠食）    85 月    86 ⺮    87 犭    88 彳    89 鱼（魚）    80 夂 （攵）
    91 广    92 忄（心）    93 火（灬）    94 氵    95 讠（訁）    96 方    97 宀    98 疒    99 礻（示）    90 衤
    01 尸    02 阝（卩）    03 女    04 又    05 纟（糹）     06 马 （馬）   07 厶    08 弓   09（序号）  00（标点符号）

    注：括号内为同类变形部件

    部件选取的顺序以汉字笔顺为准，即按笔画输入到有部件时就进行部件的输入。
    如："现"字，"王"为一部件，首笔为"一"，输入6，"王"便出现在输入框中，序号为1，所以输入1(也可以直接用鼠标点击)，这就完成"王"部件的输入；
    然后再输入下一笔"丨"，代码2，"现"便出现在候选汉字第一位，按回车或空格完成输入。"现"的代码为612。
    再如："内"字，输入前两笔代码25，"人"是一部件，首笔为"丿"，输入8，"人"出现在输入框中，序号为4，所以输入4。"内"的代码为2584。
    
* * *
    
<big>三、智能渐进方式</big>

    部件输入方式解决了大多数常用部件，大大提高了输入的效率，但有还有少部分不是很常用的部件。
    因此需要在输入过程中将一些不是很常用的多笔部件作了交互式的智能处理，即：利用"1、2、3、4、5、6"来拓展部件笔画。
    在输入过程中若在输入框中出现了要输入字的部件（偏旁部首），则这个部件的剩余代码不必再输，转为输它的后续代码。
    以下为智能渐进部件（共20个） :
    
    10 髟    12 其    13 歹    15 覀（西）    17 耳
    20 骨    24 党字头    25 黑    27 門
    30 饣    31 牜（牛生）    32 臼    33 舟    34 豸    35 角（）    36 身    37 舌    38 矢    39 鸟（鳥）
    40 气    41 立    42 门    43 米    44 学學字头
    52 子    54 癶    59 鬼
    60 革（廿）     67 走（土士）

    如，输入"物"字：
    第一笔：撇笔31，"牜"即出现在输入框中，此时"牜"的剩余代码不必再输，
    转为输"物"的后续代码（即"勿"的代码），输入353，"物"出现在候选汉字的第一位，其精简码为31353。
    
    再如，输入"鞭"字：
    "廿"为一常用部件，代码"60"，输完之后，"革"出现在输入框中，则"革"的剩余代码不必再输，
    转为输"鞭"的后续代码（即"便"的代码），输入8，"鞭"出现候选汉字的第一位，其精简码为608。
    
* * *
    
<big>四、盲打输入规则（六全码）</big>

    按照笔顺输入笔画，再结合部件的输入方式，95%以上的汉字都能在4键之内显示出来，
    若要进一步提高输入速度，逐步过渡到盲目打高速输入方式，则需掌握六码的取码方法。
    所谓六码取码方法，即每个汉字最多取六码，当汉字代码超过六码时，第六码取该汉字最后一笔代码，
    若该字最后一部分为常用部件，则取该常用部件的首笔代码。例：

    党：247535（"党"的最后一笔为"乛"，第六码取5）
    漭：946412（"漭"的最后一笔为"丨"，第六码取2）
    涯：941366（"涯"最后部分为常用部件"土"，第六码取部件"土"的首笔部件笔画代码"6"）
    骞：971120（"骞"最后部分为常用部件"马"，第六码取部件"马"的首笔部件笔画代码"0"）

    大多数常用的汉字，均不需取完所有代码便可出现在候选汉字的首位，然后按回车键直接完成输入，
    这些汉字的不完全代码称为"精简码"，多用精简码可显著加快输入的速度，从而实现高速盲打。例：

    我：简码为31，全码为312154；
    是：简码为7，全码为711218；
    实：简码为97，全码为971354；
    能：简码为07，全码为072515；
    介：简码为843，全码为8432；
    
* * *
    
<big>五、词组输入规则</big>

一、词组连续输入：（初级用户使用，注意在功能设置中打开“全笔顺输入”选项）

    用户可以方便的，随心所欲的输入词组。本输入模式十分适合初级用户使用，但如果想快速输入词组，建议同时掌握“快速词组输入”方法。
    使用词组连续输入，有以下两种方法：（建议合并为三三连接法，即三三法也要加.点号连接）

    1、三三法：词组中每个字取前3个编码，如果该字不足三个编码，则重复最后一个编码，有几个字就按序取几个字的编码
    （当然，如果该词组已经出现了，就不用再取了）例如：

    学习：443541
    力气：533311（注：“力”的编为53，由于不足三个编码，则重复最后一个编码3）
    井冈山：113253733
    一帆风顺：111703（注：只输入到“一帆”，词组就出来了，所以不用再输入下去了）

    2、连接法：词组中的每个字，用户可以输入不定长的代码，中间用“.”隔开即可，十分方便。
    每个字的代码即可是单笔画，也可以是部件代码，想怎么输就怎么输，例如：

    中国：25.251 或 75.25
    一会儿：1.34.35 或 1.84.35

    虽然词组中每个字可以输入任意长度的代码，但建议输入2－3个代码，这样更有利于定位词组。
    同时也建议尽量使用部件代码，以降低重码率，提高词组的输入速度。

二、超长词组快速输入：（熟练用户使用）二二法

    词组输入十分简单，其规则如下：
    两字词组，每字取前三码（若有汉字的代码不足三码的，则重复其最后一码补足三码）；
    三字以上词组，前两字分别取其前二码，最后一个字取其前两码
    （若有汉字的代码不足两码的，则重复其最后一码补足两码。词组输入十分简单，其规则如下：

    例如：
    我们：312824
    个人：842844（"人"字代码为"84"，不足三码，重复最后一码"4"）
    共和国：608325
    一会儿：118435（"一"字代码为"1"，不足两码，重复最后一码"1"）
    结束语：051795
    道德观念：438884
    中华人民共和国：758225
    
* * *
    
<big>    六、易错易混汉字</big>
    
    以下汉字是容易输入错误或混淆的：
    1、"末、未、耒、果"等后四笔形成的"木"形结构，其结构清晰，易于辨认，且笔画顺序与"木"相同，汉字的意义也与"木"相关，故取"木"的代码62；
    2、"都、教、考、孝"等前三笔形成的"土"形结构，其结构清晰，易于辨认，且笔画顺序与"土"相同，故取"土"的代码67；
    3、"截、戴、载、裁"等前三笔虽也形成"土"形结构，但变形严重，不易辨认，故需按其笔顺取码121；
    4、"国、因"等含"囗"的汉字，因按笔顺这些字最后才封口，故不取"口"；正确取法，第一、二笔取"丨、乛"，取码25；
    5、"密、秘"等含"必"的汉字，因按笔顺"必"为"丶乛丶丿丶"，故不取"心丿"；正确取法为按其笔顺取码45434；
    6、"其、甘、某"等的开头几笔形成的结构即非"艹"字头，也非"廿"头，需按其笔顺取码122；
    7、"里、垂、重"等最后三笔形成的"土"形结构，因其笔画顺序与"土"字旁不同（先一竖再横），故需按其笔顺取笔画代码；
    8、"段、鹤、雀"等字中有类似"亻"的结构，均不作为"亻"，需取其笔画代码32；
    9、"衰、蓑"两字中间的"口"形结构，因按笔顺先写"口"中间的一横，打乱了整个"口"的笔顺，故也不按"口"字旁处理，需取其笔画代码2511；
    10、"缶、击、出"等字最后三笔形成"山"形结构，笔顺也与"山"相同，但不易于辨认，故不取"山"字旁，需取笔画代码252；
    11、"制，刺，敝"等的左边均有类似"巾"的结构，笔顺也与"巾"相同，但不易于辨认，故不取"巾"字旁，需取笔画代码252；
    12、“冒、帽”上面不是“日”字，而是丨乛一一，这两横不连接到旁边，即2511。
    13、”有、育、膏“的下面不是”月“，而是先一竖丨乛一一，即2511。

    以下汉字和部件的笔顺容易出错：

    七：一乛 15              九：丿乛 35
    匕：丿乛 35              乃：乛丿53
    刀：乛丿 53              力：乛丿 53
    万：一乛丿 153            小：丨丿丶234
    及：丿乛丶 354            忄：丶丶丨442
    义：丶丿丶 434            车：一乛一丨1512
    巨：一乛一乛 1515         比：一乛丿乛 1535
    瓦：一乛乛丶 1554         牛：丿一一丨 3112
    牜：丿一丨一 3121         长：丿一乛丶 3154
    方：丶一乛丿 4153         火：丶丿人 4334
    为：丶丿乛丶 4354         丑：乛丨一一 5211
    爿：乛丨一丿 5213         办：乛丿丶丶 5344
    毋：乛乛丿一 5531         世：廿乛 12215
    可：一口丨 12512          龙：一丿乛丿丶 13534
    北：丨一一丿乛 21135       凸：丨一丨乛一 21251
    由：丨乛一丨一 25121       冉：丨乛丨一一 25211
    凹：丨乛丨乛一 25251       必：丶乛丶丿丶 45434
    讯：讠乛一丨 45512         出：乛丨丨乛丨 52252
    皮：乛丿丨又 53254         母：乛乛丶一丶 55414
    考：土丿一乛 121315        兆：丿丶一乛丿丶 341534
    那：乛一一丿阝 511352       里：日丨一一 2511211
    卵：丿乛丶丿卩丶 3543524    非：丨一一一 丨一一一 21112111
    官：宀丨乛一乛一 44525151   肃：乛一一丨丿丨八 51123234
    贯：乛乛丨一贝 55212534     重：丿一日丨一一 312511211
    脊：丶一丿丶人丨乛一一 4134342511
    衰：丶 一丨乛一一丿乛丿丶 4125113534
    曹：一丨乛一丨丨一日 12512212511
    爽：一丿丶丿丶丿丶丿丶人 13434343434
    兜：丿日丿乛乛一丿乛 32511355135
    敝：丶丿丨乛丨丿丶攵 43252343134
    舆：丿丨一一车乛一一一丿丶 32111512511134
    噩：一丨口口一口口一 1225125112512511
    再：一丨乛丨一一125211
    