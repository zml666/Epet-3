# git管理项目
## 1). 创建本地仓库
    创建.gitignore配置文件
    git init
    git add *
    git commit -m "xxx"

## 2). 创建github远程仓库
    New Repository
    指定名称
    创建
## 3). 将本地仓库推送到远程仓库
    git remote add origin https://github.com/zxfjd3g/170612_JSAdvance.git 关联远程仓库
    git push origin master

## 4). push本地的更新
    git add *
    git commit -m "xxx"
    git push origin master

## 5). 克隆github上的项目:
    git clone https://github.com/zxfjd3g/170612_JSAdvance.git

## 6). pull远程的更新
    git pull origin master

## 7). 撤消本地修改
    git status  查看变化
    git checkout -- xxx文件  撤消指定文件的修改
