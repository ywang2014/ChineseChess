# ChineseChess

Skip to content
This repository

    Pull requests
    Issues
    Gist

    @ywang2014

1
0

    4

ywang2014/ChineseChess forked from zhijie/ChineseChess

ChineseChess/ReadMe.txt
@zhijie zhijie on 1 Mar 2012 base code

1 contributor
92 lines (59 sloc) 3.38 KB
================================================================================
MICROSOFT 基础类库: ChineseChess 项目概述
===============================================================================

应用程序向导已为您创建了这个 ChineseChess 应用程序。此应用程序不仅演示 Microsoft 基础类的基本使用方法，还可作为您编写应用程序的起点。

本文件概要介绍组成 ChineseChess 应用程序的每个文件的内容。

ChineseChess.vcproj
这是使用应用程序向导生成的 VC++ 项目的主项目文件。 
它包含生成该文件的 Visual C++ 的版本信息，以及有关使用应用程序向导选择的平台、配置和项目功能的信息。

ChineseChess.h
这是应用程序的主要头文件。它包括其他项目特定的头文件(包括 Resource.h)，并声明 CChineseChessApp 应用程序类。

ChineseChess.cpp
这是包含应用程序类 CChineseChessApp 的主要应用程序源文件。

ChineseChess.rc
这是程序使用的所有 Microsoft Windows 资源的列表。它包括 RES 子目录中存储的图标、位图和光标。此文件可以直接在 Microsoft Visual C++ 中进行编辑。项目资源位于 2052 中。

res\ChineseChess.ico
这是用作应用程序图标的图标文件。此图标包括在主要资源文件 ChineseChess.rc 中。

res\ChineseChess.rc2
此文件包含不在 Microsoft Visual C++ 中进行编辑的资源。您应该将不可由资源编辑器编辑的所有资源放在此文件中。

/////////////////////////////////////////////////////////////////////////////

对于主框架窗口:
项目包含标准 MFC 界面。

MainFrm.h, MainFrm.cpp
这些文件包含框架类 CMainFrame，该类派生自
CFrameWnd 并控制所有 SDI 框架功能。

res\Toolbar.bmp
此位图文件用于为工具栏创建平铺图像。
初始工具栏和状态栏在 CMainFrame 类中构造。使用资源编辑器编辑此工具栏位图，并更新 ChineseChess.rc 中的 IDR_MAINFRAME TOOLBAR 数组以添加工具栏按钮。
/////////////////////////////////////////////////////////////////////////////

应用程序向导创建一个文档类型和一个视图:

ChineseChessDoc.h，ChineseChessDoc.cpp - 文档
这些文件包含 CChineseChessDoc 类。编辑这些文件可以添加特殊文档数据并可实现文件保存和加载(通过 CChineseChessDoc::Serialize)。

ChineseChessView.h，ChineseChessView.cpp - 文档的视图
这些文件包含 CChineseChessView 类。
CChineseChessView 对象用于查看 CChineseChessDoc 对象。





/////////////////////////////////////////////////////////////////////////////

其他功能:

ActiveX 控件
应用程序包括对使用 ActiveX 控件的支持。

打印及打印预览支持
应用程序向导已通过从 MFC 库调用 CView 类中的成员函数，生成了用于处理打印、打印设置和打印预览命令的代码。

/////////////////////////////////////////////////////////////////////////////

其他标准文件:

StdAfx.h，StdAfx.cpp
这些文件用于生成名为 ChineseChess.pch 的预编译头 (PCH) 文件和名为 StdAfx.obj 的预编译类型文件。

Resource.h
这是标准头文件，它定义新的资源 ID。
Microsoft Visual C++ 读取并更新此文件。

ChineseChess.manifest
	应用程序清单文件供 Windows XP 用来描述应用程序
	对特定版本并行程序集的依赖性。加载程序使用此
	信息从程序集缓存加载适当的程序集或
	从应用程序加载私有信息。应用程序清单可能为了重新分发而作为
	与应用程序可执行文件安装在相同文件夹中的外部 .manifest 文件包括，
	也可能以资源的形式包括在该可执行文件中。 
/////////////////////////////////////////////////////////////////////////////

其他注释:

应用程序向导使用“TODO:”指示应添加或自定义的源代码部分。

如果应用程序在共享的 DLL 中使用 MFC，则需要重新发布这些 MFC DLL；如果应用程序所用的语言与操作系统的当前区域设置不同，则还需要重新发布对应的本地化资源 MFC90XXX.DLL。有关这两个主题的更多信息，请参见 MSDN 文档中有关 Redistributing Visual C++ applications (重新发布 Visual C++ 应用程序)的章节。

/////////////////////////////////////////////////////////////////////////////

    Status API Training Shop Blog About Pricing 

    © 2015 GitHub, Inc. Terms Privacy Security Contact Help 

