# Git_and_Github

## Installing Git

>The first step on the way to using Git is to install it! The directions found in the Git documentation below are pretty thorough and helpful, check them out for the best method of getting Git onto your platform of choice.



### [Git Download Page](https://git-scm.com/downloads)


### [Git Installation for each platform](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

___

### [Git documentation](https://git-scm.com/docs/gittutorial)



### [Git Book](https://git-scm.com/book/en/v2)

> Free Book on Git

___

## Advanced Git Cheat Sheet

[git commit -a](https://git-scm.com/docs/git-commit#Documentation/git-commit.txt---all)
> Stages files automatically

[git log -p](https://git-scm.com/docs/git-log#_generating_patch_text_with_p)
> Produces patch text

[git show](https://git-scm.com/docs/git-show)
> Shows various objects

[git diff](https://git-scm.com/docs/git-diff)
> Is similar to the Linux `diff` command, and can show the differences in various commits

[git diff --staged](https://git-scm.com/docs/git-diff)
> An alias to --cached, this will show all staged files compared to the named commit

[git add -p](https://git-scm.com/docs/git-add)
> Allows a user to interactively review patches to add to the current commit

[git mv](https://git-scm.com/docs/git-mv)
> Similar to the Linux `mv` command, this moves a file

[git rm](https://git-scm.com/docs/git-rm)
> Similar to the Linux `rm` command, this deletes, or removes a file

___

## Git Revert Cheat Sheet

> [git checkout](https://git-scm.com/docs/git-checkout) is effectively used to switch branches.

> [git reset](https://git-scm.com/docs/git-reset#_examples) basically resets the repo, throwing away some changes. It’s somewhat difficult to understand, so reading the examples in the documentation may be a bit more useful.

> There are some other useful articles online, which discuss more aggressive approaches to [resetting the repo](https://jwiegley.github.io/git-from-the-bottom-up/3-Reset/4-doing-a-hard-reset.html).

> [git commit --amend](https://git-scm.com/docs/git-commit#Documentation/git-commit.txt---amend) is used to make changes to commits after-the-fact, which can be useful for making notes about a given commit.

> [git revert](https://git-scm.com/docs/git-revert) makes a new commit which effectively rolls back a previous commit. It’s a bit like an undo command.

> There are a [few ways](https://git-scm.com/book/en/v2/Git-Basics-Undoing-Things) you can rollback commits in Git.

> There are some interesting considerations about how git object data is stored, such as the usage of sha-1. 

### Feel free to read more here:

* https://en.wikipedia.org/wiki/SHA-1

* https://github.blog/2017-03-20-sha-1-collision-detection-on-github-com/

___

## Git Branches and Merging Cheat Sheet