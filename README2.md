# malo安裝 python3.6 + jupyter on Heroku的memo

- 安裝後容易，只要按個deploy就行了

- 但…如果有想用的pandas, matplotlib…等package要用，每次都要到terminal中安裝，很煩

- 因此可以修改"environment.yml"如下：
<pre><code>
  - pip:
    - pgcontents
    - twstock
    - pandas
    - matplotlib
    - pymongo
    - imgurpython
    - SQLAlchemy
    - PyMySQL
    - git+git://github.com/ipython-contrib/jupyter_contrib_nbextensions.git
</code></pre>
