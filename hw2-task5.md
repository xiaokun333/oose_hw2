1. mkdir hw2-task5
cd hw2-task5

2. git init
3. emacs README.md
4.git add README.md
git commit -m "added readme"

5. made new repo on github
6. git push --set-upstream origin master

7. edited README on github and locally
8. git commit -m "edited local readme"
git push
git status
emacs README.md
git add .
git commit -m "resolving conflict"

9. 
10. go to git repo
11. created issue "Making feature 1!"
12. git checkout -b feature1
13. emacs FEATURE1.md
14. git commit -m "added feature 1"
 git push
 git push --set-upstream origin feature1
15. created a new pull request on git
16. approve pull request on git
17. close issue
18.  git pull

commit 3d950ebf529bdc5b9219f0568d9766235a6aa036
Merge: 309e1d3 4fcdca9
Author: xiaokun333 <70614708+xiaokun333@users.noreply.github.com>
Date:   Wed Sep 15 19:53:08 2021 -0400

    Merge pull request #2 from xiaokun333/feature1
    
    added feature 1

commit 4fcdca92457e882b14599672d1ff1965aca8b9d1
Author: xiaokun333 <xyu61@jhu.edu>
Date:   Wed Sep 15 19:49:21 2021 -0400

    added feature 1

commit 309e1d32ecc15271d37beec26e49e93694b1e5bb
Merge: 9acd6a3 c3e87c4
Author: xiaokun333 <xyu61@jhu.edu>
Date:   Wed Sep 15 19:38:45 2021 -0400

    resolving conflict

commit 9acd6a3d62c88f3d61c4018882ae95d57624766e
Author: xiaokun333 <xyu61@jhu.edu>
Date:   Wed Sep 15 19:30:36 2021 -0400

    edited local readme

commit c3e87c446d85b30bd47cbce94af7ed7e1f5c16da
Author: xiaokun333 <70614708+xiaokun333@users.noreply.github.com>
Date:   Wed Sep 15 19:29:23 2021 -0400

    edited remote
    
    edited remote

commit 461d465816134258b83b80d0c4e7e5bc73e8c5ac
Author: xiaokun333 <xyu61@jhu.edu>
Date:   Wed Sep 15 19:16:56 2021 -0400

    added readme
