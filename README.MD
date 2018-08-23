<!--
Marked Style: Github
-->

# GitRuler Section D

This repository is section D of the [GitRuler exercises](https://github.com/UOL-CS/gitruler-exercises).

In this exercise we will learn about tagging and viewing differences between commits and files within the repository history

## Introduction

If you do not already have a your own repository for these exercises [fork this repository](https://help.github.com/articles/fork-a-repo/). Clone this repository

At any time you can run gitruler to check your progress. From the command line run:

`java -jar <path to gitruler.jar>`

For more information on running gitruler look at the [project repository](https://github.com/rcraggs/gitruler).

## Instructions

1. After cloning the repository change into the directory on a [command line](https://www.techopedia.com/definition/3337/command-line-interface-cli).
2. Run gitruler to initialise the exercise.


## Tagging commits

1. Tag HEAD, the current commit with the name "first-tag".

## Viewing at the git history log

2. Look at the git history log to find the commit with the message "This is the second commit that you need to tag"
3. Check out that commit
4. Tag that commit with the name "second-tag".
5. Check out the latest commit on the master branch.

## Comparing commits 

1. Look at the git history log for the file `chinese-years.txt`
2. Compare each commit to its previous one (its parent commit) to find which commit added the line "1978: Horse".
3. Check out that commit
4. Tag it with the name "1978-tag"

## Submitting the results

Once the exercise is complete, push this repository to the remote. If there are tags or multiple branches for an exercise, make sure that you push them all. 

To ensure that you have you correctly pushed everything that you need to, you could clone the remote repository into a separate folder and re-run gitruler.

## Resources

The following are example of the many free resources that will explain how to perform the actions required for this exercise.

1. Tagging versions [https://githowto.com/tagging_versions](https://githowto.com/tagging_versions).
2. Viewing the git history log [https://githowto.com/history](https://githowto.com/history)
3. Checking out a commit or the latest commit on master [https://github.com/francopestilli/life/wiki/Switch-to-a-previous-state-of-the-repository](https://github.com/francopestilli/life/wiki/Switch-to-a-previous-state-of-the-repository)
4. Viewing the changes to a file made by a commit: It's easy to Google for this. You will need to learn to use the [diff](https://www.atlassian.com/git/tutorials/saving-changes/git-diff) command.