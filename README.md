***SEED for Angular 1 Projects with Gulp***
* Voraussetzungen:
<pre><code>
$
$ sudo apt-get install -y nodejs
$ nodejs --version      //v0.10.24
$
$ sudo apt-get install -y npm
$ npm --version         //1.3.10
$
$ npm init                      //erzeugt package.json, die bearbeitet wird
$ sudo npm install -g gulp      //should be installed globally 
$ npm install --save-dev gulp   //and locally
$ npm install --save-dev gulp-load-plugins
$ npm install --save-dev del
$ npm install --save-dev event-stream    
$ npm install --save-dev main-bower-files
$ npm install --save-dev gulp-print
$ npm install --save-dev q

        

</code></pre>

* planned Folder Structure:
<pre><code>

        /project
            package.json
            bower.json
            gulpfile.js
            index.html
            
            /assets
                /images
                
            /app (src)
                app.js
                
                /components
                    /assets (pictures)
                    /global (app wide data, Kopfdaten)
                        /user
                            /login
                        /auftrag
                        /kunde 
                        /fahrzeug
                    /header
                    /main
                        /epc
                            /data
                            /action
                        ...
                    /navbar
                    /zbitbar (footer)
                    
            server.js  
                  
            /devServer      
                   
            /dist.dev (build)
                index.html
                app.js
                
                /bower_components
                /components
                /styles
                        
            /dist.prod (dist)  
                index.html
                  
                /scripts
                    app.min.js
                    vendor.min.js
                /styles
                    app.min.css               
</code></pre>

<pre><code>
</code></pre>

<pre><code>
</code></pre>

