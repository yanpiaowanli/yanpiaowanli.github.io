## Test Blog

First, find the SSH version clone link of the project files you need to clone on the GitHub page, for example `git@github.com:yanpiaowanli/yanpiaowanli.github.io.git`

Then, open Git Bash (or cmd) in the target folder (for example `E:\projects\blog`) and enter the following command

```cmd
git clone git@github.com:example
```

For example, in the above example, we use the following code

```cmd
git clone git@github.com:yanpiaowanli/yanpiaowanli.github.io.git
```

Next, you can open the folder in VS, in this example it is `E:\projects\blog`. VS will automatically generate a `.vs` folder in that path.

After that, you can modify the files locally. For example, we modify `E:\projects\blog\yanpiaowanli.github.io\_config.yml`

After the modification, right-click in the project's root directory (in this example `E:\projects\blog\yanpiaowanli.github.io`) and open Git GUI

In Git GUI, click Rescan and then Stage Changed in sequence. Then enter the Commit text in the bottom right corner in the following format

```Commit
First line: Summarize in one sentence what this update has done
Second line: Leave empty
Following Line: Explain in detail why the above update was made
```

After entering the text, click Push in Git GUI, and in the pop-up window, click OK.