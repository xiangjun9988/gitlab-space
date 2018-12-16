## 这个第一个版本功能

涉及到协作，自然会涉及到分支，关于分支，大概有展示分支，切换分支，创建分支，删除分支这四种操作。

git branch列出所有本地分支

git branch -r列出所有远程分支

git branch -a列出所有本地分支和远程分支

git branch 新建一个分支，但依然停留在当前分支

git checkout -b 新建一个分支，并切换到该分支

git branch --track 新建一个分支，与指定的远程分支建立追踪关系

git checkout 切换到指定分支，并更新工作区

git branch -d 删除分支

git push origin --delete 删除远程分支

关于分支的操作虽然比较多，但都比较简单好记。
add相关命令很简单，主要实现将工作区修改的内容提交到暂存区，交由git管理。

git add .添加当前目录的所有文件到暂存区

git add 添加指定目录到暂存区，包括子目录

git add 添加指定文件到暂存区
