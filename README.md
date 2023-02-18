This is the Recipe Project. 
I've created a repository on Git and cloned it on my local machine using SSH without much problem.

However, it's hard to remember the workflow of commits. 

1) "git status" command will show the files that are not staged yet as they appear in RED. It means they are on a local machine, but not on GitHub.

2) "git add (file name)" adds the file to the staging area (aka waiting room) in Git.
If you repeat git status, the file will change from red to green.

3) git commit -m "Commit description" is the command to commit the file that undergone changes with a descriptive message not esceeding 50 chars. By calling "git status": output "nothing to commit, working tree clean" will indicate that the commit was successful.

4) "git log" will show the details of the whole beforementioned process.