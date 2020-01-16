# git-gen-ignore
Small git tool to generate .gitignore files using [gitignore.io](http://www.gitignore.io/)

# Installation

1. Install [Stack](https://docs.haskellstack.org/en/stable/README/)
2. `mkdir ~/bin`
3. Copy git-gen-ignore into `~/bin`
4. `sudo chmod +x ~/bin/git-gen-ignore`
5. Add `PATH=$PATH:$HOME/bin` at the end of your `~/.bashrc`
6. To search possible arguments, use `git genignore list [list of search terms separated by a space]`
7. Use with `git gen-ignore [list of OS, IDE, Programming languages separated by a space]`

# Example
## Search possible arguments
`git genignore list hask intell`
## Generate `.gitignore`
In a repository, run `git gen-ignore haskell intellij` to generate a gitignore equivalent to [gitignore.io/api/haskell,intellij](https://www.gitignore.io/api/haskell,intellij)
