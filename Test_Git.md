# Семинар 3



## Команды
git add .
git init
git remote add origin git@github.com:yvv4git/Lesson3.git
git branch -M master
git add .
git commit -m "Add lesson3 md file"
git push -u origin master

git add
Moves changes from the working directory to the staging area. This gives you the opportunity to prepare a snapshot before committing it to the official history.

git branch
This command is your general-purpose branch administration tool. It lets you create isolated development environments within a single repository.

git checkout
In addition to checking out old commits and old file revisions, git checkout is also the means to navigate existing branches. Combined with the basic Git commands, it’s a way to work on a particular line of development.

git clean
Removes untracked files from the working directory. This is the logical counterpart to git reset, which (typically) only operates on tracked files.

git clone
Creates a copy of an existing Git repository. Cloning is the most common way for developers to obtain a working copy of a central repository.

git commit
Takes the staged snapshot and commits it to the project history. Combined with git add, this defines the basic workflow for all Git users.

git commit --amend
Passing the --amend flag to git commit lets you amend the most recent commit. This is very useful when you forget to stage a file or omit important information from the commit message.

git init
Initializes a new Git repository. If you want to place a project under revision control, this is the first command you need to learn.

git merge
A powerful way to integrate changes from divergent branches. After forking the project history with git branch, git merge lets you put it back together again.