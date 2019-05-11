git 版本工具 学习笔记

Git 常用命令
  
git init 初始化git将该文件编程一个git仓库

git status 查看状态

git add [文件名] 将文件添加到仓库（暂存区）

git commit 把文件提交到仓库

git reset HEAD 撤销暂存区内容

git diff 查看区别

git rm 删除 git mv 移动或重命名文件

git branch [分支名] 不跟分支名查看分支，跟分支名创建分支

git checkout [分支名] 切换分支

git merge 合并分支

git log 提交日志

git log --oneline

git tag -a v1.0 编辑模式输入版本的说明信息，:wq保存退出

git log --oneline -decorate --graph 查看标签信息

git tag 查看历史版本


特点：
  1、开源的分布式的版本控制系统
  2、无需服务端支持
  
git 和 svn 区别
  1、Git是分布式，SVN不支持
  2、Git以元数据存储，SVN以文件存储

Git概念
  工作区：版本控制目录
  暂存区：.git/index 存储新增
  版本库：.git

git常用命令
  


