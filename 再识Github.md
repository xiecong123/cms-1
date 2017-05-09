## 详细了解Github

> **1,个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？**
+ New repository 创建新的仓库
+ import repository
+ New gist 创建代码片段
+ New organization 创建组织

> **2，如何能将仓库中的html文件直接解析成页面？**
>> 选择master brash，上方网址超链接得到页面

> **3，如何删除仓库**
>> setting中选择detele this repository,重复确认

> **4，Bash是什么操作系统的命令**
>> linux

> **5,Pwd是什么命令**
>> 打开文件位置

> **6,Cd是什么命令**
>> 改变目录

> **7,Echo是什么命令**
>> 打印输出

> **8,配置git用户名的命令**
>> git config --global user.name "youname"

> **9,配置邮箱的命令**
>> git config --global user.email "youeamil@email.com"

>**10,命令行换行方式**
>> \

> **11,命令行终结方式**
>> ctrl+c

> **12，使用命令行比GUI方式有何优势**
>> 速度快，使用便捷

> **13，提交到本地仓库时为什么有暂存区**
>> 暂存区: 修改都是进入到暂存区了,肉眼不可见 通过 $ git status  可以看到修改的状态，修改只能在被add 到暂存区以后才能被提交

> **14，新建代码仓库的命令**
>> git init

> **15，git clone [url] 这个命令的作用是**
>> 下载一个项目和它的整个代码历史

> **16，添加指定文件到暂存区的命令**
>> git add [file1][file2]

> **17，删除工作区文件，并且将这次删除放入暂存区的命令**
>> git rm [file1][file2]

> **18，改名文件，并且将这个改名文件放入暂存区的命令**
>> git mv [file-origin][file-renamed]

> **19，提交暂存区到仓库的命令**
>> git commit -m [message]

> **20，直接从工作区提交到仓库的命令**
>> git commit -a -m [message]

> **21，显示变更信息的命令**
>> git status

> **22，查看历史信息的命令**
>> git log

> **23，Commit的意义是**
>> comiit 是将本地修改保存到本地仓库中

> **24，Pull的意义是**
>> 取回远程主机某个分支的更新，再与本地的指定分支合并。

> **25，Push的意义是**
>> git push 将本地仓库修改推送到服务器上的仓库中
