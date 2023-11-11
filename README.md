<!-- https://www.freecodecamp.org/news/gitignore-file-how-to-ignore-files-and-folders-in-git/ -->
# git_test
testing the git different config


git status

git add .
git commit -m "Testing the Commit"
git push 


<!-- Remove the File only in Remote Repo i.e. GITHUB but not in Local GIT -->
git rm --cached -r testing_folder
git rm --cached filename.txt
git commit -m "Need to commit"
git push 

Certainly! Here are some basic Git commands that you might find useful:

1. **git init**: Initializes a new Git repository in the current directory.

   ```bash
   git init
   ```

2. **git clone**: Creates a copy of a remote repository on your local machine.

   ```bash
   git clone <repository_url>
   ```

3. **git add**: Adds changes in your working directory to the staging area.

   ```bash
   git add <filename>
   ```

   To add all changes:

   ```bash
   git add .
   ```

4. **git commit**: Commits changes from the staging area to the repository.

   ```bash
   git commit -m "Your commit message"
   ```

5. **git status**: Shows the status of changes as untracked, modified, or staged.

   ```bash
   git status
   ```

6. **git pull**: Fetches changes from a remote repository and merges them into the current branch.

   ```bash
   git pull
   ```

7. **git push**: Pushes changes from your local repository to a remote repository.

   ```bash
   git push origin <branch_name>
   ```

8. **git branch**: Lists existing branches or creates a new branch.

   ```bash
   git branch
   ```

   To create a new branch:

   ```bash
   git branch <branch_name>
   ```

9. **git checkout**: Switches to a different branch.

   ```bash
   git checkout <branch_name>
   ```

   To create and switch to a new branch:

   ```bash
   git checkout -b <new_branch_name>
   ```

10. **git merge**: Merges changes from one branch into another.

    ```bash
    git merge <branch_name>
    ```

11. **git log**: Shows a log of commits.

    ```bash
    git log
    ```

12. **git remote**: Shows a list of remote repositories.

    ```bash
    git remote -v
    ```

These are just some of the basic Git commands. Git has a rich set of features, so depending on your workflow, you might need additional commands and options. Don't forget to check the Git documentation for more details and options for each command.

https://stackoverflow.com/questions/9529497/what-is-origin-in-git
git remote show origin

git remote rename origin TEST_REPO

git init - initializes a new git repository
git add - adds files to the index
git commit - commits changes to the index
git status - shows the status of the working tree and the index
git log - shows the history of commits
git branch - creates and lists branches
git checkout - switches to a branch
git merge - merges two branches
git pull - fetches changes from a remote repository and merges them into the current branch
git push - pushes changes from the current branch to a remote repository
