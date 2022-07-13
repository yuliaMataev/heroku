"# heroku"

one time:

```
 # add project to git and then
 heroku login
 heroku git:remote -a hackeruclass11722
```

Every update:

```
git add .
git commit -am "version xyz with changes: a,b,c"
git push                # for github
git push heroku main    # deploy using heroku
```
