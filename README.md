# Work

- [JavaScript](#JavaScript)
  - [NVM](#nvm) 
- [Python 1](#Python-1)
  - [virtualenv](#virtualenv) 
- [Python 2](#Python-2)

## JavaScript

## nvm

<p>JavaScript'in farklı versiyonlarını kullanmak için kullanılır.</p>

<h5>Kurulum:</h5>

<ul>
  <li>Windows: <a href="https://github.com/coreybutler/nvm-windows/releases">nvm-windows</a></li>
  <li>Linux: <code>curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.2/install.sh | bash</code> </li>
</ul>

<p>Kurulumdan sonra Terminal(Shell)'i yeniden başlatın. Linux için: <code>exec "$SHELL"</code></p>
<p>Sürümü kontrol edin: <code>nvm --version</code></p>

<h5>Kullanım</h5>

<ul>
  <li><code>nvm install {sürüm} </code> Belirlenen sürümü indirmenizi olanak tanır. Örnek: <code>nvm install 8.0.0</code></li>
  <li><code>nvm use {sürüm} </code> Belirlenen sürümü kullanır.</li>
  <li><code>nvm run {sürüm} app.js </code> 'app.js'yi belirlenen sürüm ile çalıştırır.</li>
</ul>

## Python-1

## virtualenv

<p>Python'un farklı sürümlerini kullanarak sanal bir çalıştırma ortamı oluşturur. Böylece ana cihaza yüklemeye gerek kalmaz.</p>

```mermaid
graph LR
  A[virtualenv] -->|Python3.9| Sanal Çalışma Dizini
  B[virtualenv] -->|Python3.5| Sanal Çalışma Dizini
  C[virtualenv] -->|Python3.0| Sanal Çalışma Dizini

```


<h5>Kurulum:</h5>

<ul>
  <li>Windows: <code>pip install virtualenv</code></li>
  <li>Linux: <code>sudo apt install python3-virtualenv</li> ya da <code>pip install virtualenv</code>
</ul>

<h5>Kullanım</h5>

<ul>
  <li><code>virtualenv {} </code> Belirlenen sürümü indirmenizi olanak tanır. Örnek: <code>nvm install 8.0.0</code></li>
  <li><code>nvm use {sürüm} </code> Belirlenen sürümü kullanır.</li>
  <li><code>nvm run {sürüm} app.js </code> 'app.js'yi belirlenen sürüm ile çalıştırır.</li>
</ul>
