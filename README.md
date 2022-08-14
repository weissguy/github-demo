# github-demo
Demo project to practice essential Git skills.


**0. Let's Get Git Basics**
- *Git* - A version control system, used for collaborative software development.
  - Git lets us view a project's progress over time.
  - Because Git stores history, we can revert to older versions of the project.


**1. What Even is a Repository?**
- *Repository* - A location to store all the code for one project.
  - For FRC, we make a new repo for every individual robot.
  - This repo's name is descriptive and simple (as it should be) -- "github-demo"


**2. Your First Commit**
- *Commit* - An uploaded set of changes to a project, which is permanently stored in Git.
  - Commits only store changes since the last commit, NOT entire file contents.
- Steps:
  - Create a new file named "file.txt"
  - Write a few lines of text into the file
  - Save the file
  - Stage changes to the file
  - Commit (with a helpful, detailed message :)
  
  
**3. Branching Off**
- *Branch* - A separate area of the repository, which stores commits separate from the main branch.
  - Branches are useful for developing and testing individual features, subsystems, etc.
  - Rule of thumb is to keep the main branch 100% functional--no new features
- Steps:
  - Create a new branch off of main named "test"
  - Open "file.txt", edit one of the lines of code, and save the file
  - Stage changes to the file
  - Commit to the "test" branch
  
  
 **4. Merging Back**
- Once a branch is fully operational, we can merge it back with the main branch
- Must issue a pull request when working on a group repository
  - B/c oftentimes conflicts must be resolved
- Steps:
  - Merge "test" with main
  - When prompted to resolve conflicts, save the new code from the "test" branch
