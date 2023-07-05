# actividadGit

Profesor:Alejandro Recalde
Curso:4to B                         
                     <br> <br>  *ACTIVIDAD GIT*



En un documento de google realicen lo siguiente:<br>
1)Investigación básica de Git:<br>
a. ¿Qué es Git y para qué se utiliza?<br>
b. ¿Cuáles son las principales características de Git?<br>
c. ¿Qué es un sistema de control de versiones?<br>
d. ¿Cuál es la diferencia entre Git y otros sistemas de control de versiones?<br>
2)Instalación y configuración de Git:<br>
a. Investiga cómo instalar Git en diferentes sistemas operativos (Windows, macOS, Linux).<br>
b. Explica los pasos para configurar tu nombre de usuario y dirección de correo electrónico en Git.<br>
3)Comandos básicos de Git:<br>
a. Investiga los comandos git init, git add, git commit y git status. Explica qué hacen y cómo se utilizan.<br>
b. Describe los comandos git log y git diff para ver el historial de cambios y las diferencias entre versiones, respectivamente.<br>
4)Trabajando con repositorios remotos:<br>
a. Investiga cómo clonar un repositorio remoto con git clone.<br>
b. Explica cómo trabajar con ramas utilizando los comandos git branch, git checkout y git merge.<br>
c. Investiga cómo subir tus cambios locales a un repositorio remoto con git push.<br>
5)Colaboración en Git:
a. Investiga cómo trabajar en equipo en un repositorio remoto utilizando ramas y fusiones.<br>
b. Explica qué son las solicitudes de extracción (pull requests) y cómo se utilizan para revisar y aprobar cambios.<br>
Recuerden que pueden utilizar cualquier medio que encuentren siempre y cuando este referido en el documento. El trabajo es individual.


1-a)El Git es un sistema de control de versiones distribuido y se utiliza para cuando nuestras aplicaciones o páginas web tienen una gran cantidad de archivos de código fuente.

b)Git tiene la característica de ser un sistema de control de versiones con repositorios distribuidos. Esto quiere decir que cada uno de los integrantes de un proyecto tiene una copia exacta del repositorio y no solamente una copia de los archivos con los que haya trabajado. 

c)Git es un Sistema de Control de Versiones Distribuido (DVCS) utilizado para guardar diferentes versiones de un archivo (o conjunto de archivos) para que cualquier versión sea recuperable cuando lo desee. Git también facilita el registro y comparación de diferentes versiones de un archivo.

d)A diferencia de la mayoría de los otros sistemas de control de versiones (VCS), git almacena cada versión guardada como una 'instantánea' en lugar de una lista de los cambios realizados en cada archivo.

2)En Windows, sólo tienes que descargar el instalador y ejecutarlo. Sigue estos sencillos pasos para hacerlo:
Descarga el instalador de GIT para Windows.
Una vez que hayas descargado el instalador, haz doble clic sobre el ejecutable para que comience el proceso de instalación y sigue las instrucciones que te aparecerán en pantalla. Al igual que cualquier otro programa, tendrás que dar “Next” (siguiente) en varias ocasiones hasta que aparezca la opción “Finish” (terminar) para completar la instalación.
Ahora tienes que abrir el símbolo de sistema y escribir los siguientes comandos en la terminal:
 
git config --global user.name "Tu nombre"
git config --global user.email "ejemplo@email.com"
Instalar GIT en MacOS

Hay muchas formas de realizar la instalación en un equipo con Mac. De hecho, hay una probabilidad de que GIT ya esté instalado en tu equipo si tienes el XCode instalado. Ejecuta el siguiente comando en la terminal para revisar si ya está instalado:
git - -version
Si tienes una salida como git versión 2.12.0 (Apple Git-66), entonces estas de suerte. Pero si este no es el caso, sigue los siguientes pasos:
Descarga el instalador oficial par Mac.
Sigue las instrucciones que te aparecerán en el programa de instalación.
Al finalizar el proceso de instalación del instalador, vuelve a revisar usando el comando git – -version para confirmar si la instalación se ha hecho correctamente.
Ahora ejecuta los siguientes comandos en la terminar para configurar tu correo y el nombre de usuario que están asociados a tu cuenta GIT:
 git config --global user.name "Tu nombre"

git config --global user.email "ejemplo@email.com"

Git
Feb 27, 2023
Gustavo B.
2min Leer
Cómo instalar GIT en Windows, MacOS y Linux
En el siguiente tutorial aprenderás la forma más simple de instalar GIT en diferentes sistemas operativos: Windows, MacOS y Linux. ¡Vayamos a ello!

Tabla de Contenidos
Instalar GIT en Windows
Instalar GIT en MacOS
Instalar GIT en Linux
Instalar GIT en Windows

En Windows, sólo tienes que descargar el instalador y ejecutarlo. Sigue estos sencillos pasos para hacerlo:
Descarga el instalador de GIT para Windows.
Una vez que hayas descargado el instalador, haz doble clic sobre el ejecutable para que comience el proceso de instalación y sigue las instrucciones que te aparecerán en pantalla. Al igual que cualquier otro programa, tendrás que dar “Next” (siguiente) en varias ocasiones hasta que aparezca la opción “Finish” (terminar) para completar la instalación.
Ahora tienes que abrir el símbolo de sistema y escribir los siguientes comandos en la terminal:
 git config --global user.name "Tu nombre"

git config --global user.email "ejemplo@email.com"

 Recuerda que debes de cambiar Tu Nombre y ejemplo@email.com por tu información.


¡Y listo! Ya has instalado GIT en Windows.
Instalar GIT en MacOS

Hay muchas formas de realizar la instalación en un equipo con Mac. De hecho, hay una probabilidad de que GIT ya esté instalado en tu equipo si tienes el XCode instalado. Ejecuta el siguiente comando en la terminal para revisar si ya está instalado:
git - -version
Si tienes una salida como git versión 2.12.0 (Apple Git-66), entonces estas de suerte. Pero si este no es el caso, sigue los siguientes pasos:
Descarga el instalador oficial par Mac.
Sigue las instrucciones que te aparecerán en el programa de instalación.
Al finalizar el proceso de instalación del instalador, vuelve a revisar usando el comando git – -version para confirmar si la instalación se ha hecho correctamente.
Ahora ejecuta los siguientes comandos en la terminar para configurar tu correo y el nombre de usuario que están asociados a tu cuenta GIT:
 git config --global user.name "Tu nombre"

git config --global user.email "ejemplo@email.com"

 Recuerda reemplazar Tu nombre y ejemplo@emial.com y agregar la información de tu cuenta.


Instalar GIT en Linux
Si eres un usuario de Linux, tal vez estés acostumbrado a instalar softwares y paquetes usando los comandos apt-get o yum install. GIT no es la excepción.
Para usuarios de Ubuntu/Debian (apt-get):
Abre la terminal y ejecuta los siguientes comandos:
 Sudo apt-get update

Sudo apt-get install git


Verifica que la instalación se haya hecho correctamente usando el comando: git –version.
A continuación, ejecuta los siguientes comandos en la terminal para poder configurar tu correo y nombre de usuario que están asociados a tu cuenta GIT:
 git config --global user.name "Tu nombre"

git config --global user.email "ejemplo@email.com".

 Recuerda cambiar Tu nombre y ejemplo@email.com por los datos de tu cuenta GIT

3)1. Git clone <br>
Git clone es un comando para descargarte el código fuente existente desde un repositorio remoto (como Github, por ejemplo). En otras palabras, Git clone básicamente realiza una copia idéntica de la última versión de un proyecto en un repositorio y la guarda en tu ordenador.<br>
2. Git branch <br>
Las ramas (branch) son altamente importantes en el mundo de Git. Usando ramas, varios desarrolladores pueden trabajar en paralelo en el mismo proyecto simultáneamente. Podemos usar el comando git branch para crearlas, listarlas y eliminarlas.<br>
3. Git checkout <br>
Este es también uno de los comandos más utilizados en Git. Para trabajar en una rama, primero tienes que cambiarte a ella. Usaremos git checkout principalmente para cambiarte de una rama a otra. También lo podemos usar para chequear archivos y commits.<br>
4. Git status <br>
El comando de git status nos da toda la información necesaria sobre la rama actual.<br>
5. Git add <br>
Cuando creamos, modificamos o eliminamos un archivo, estos cambios suceden en local y no se incluirán en el siguiente commit (a menos que cambiemos la configuración).<br>
6. Git commit <br>
Este sea quizás el comando más utilizado de Git. Una vez que se llega a cierto punto en el desarrollo, queremos guardar nuestros cambios (quizás después de una tarea o asunto específico).<br>  
Git commit es como establecer un punto de control en el proceso de desarrollo al cual puedes volver más tarde si es necesario.
También necesitamos escribir un mensaje corto para explicar qué hemos desarrollado o modificado en el código fuente.<br>
7. Git push <br>
Después de haber confirmado tus cambios, el siguiente paso que quieres dar es enviar tus cambios al servidor remoto. Git push envía tus commits al repositorio remoto.<br>
8. Git pull <br>
El comando git pull se utiliza para recibir actualizaciones del repositorio remoto. Este comando es una combinación del git fetch y del git merge lo cual significa que cundo usemos el git pull recogeremos actualizaciones del repositorio remoto (git fetch) e inmediatamente aplicamos estos últimos cambios en local (git merge).<br>
9. Git revert <br>
A veces, necesitaremos deshacer los cambios que hemos hecho. Hay varias maneras para deshacer nuestros cambios en local y/o en remoto (dependiendo de lo que necesitemos), pero necesitaremos utilizar cuidadosamente estos comandos para evitar borrados no deseados.<br>
10. Git merge <br>
Cuando ya hayas completado el desarrollo de tu proyecto en tu rama y todo funcione correctamente, el último paso es fusionar la rama con su rama padre (dev o master). Esto se hace con el comando git merge.<br>
Git merge básicamente integra las características de tu rama con todos los commits 
realizados a las ramas dev (o master).  Es importante que recuerdes que tienes que estar en esa rama específica que quieres fusionar  con tu rama de características.
Clonar un repositorio


En GitHub.com, navega a la página principal del repositorio.


Encima de la lista de archivos, haz clic en
Código.

 


Copia la dirección URL del repositorio.


Para clonar el repositorio con HTTPS, en "HTTPS", haz clic en
.


Para clonar el repositorio mediante una clave SSH, incluido un certificado emitido por la entidad de certificación SSH de la organización, haz clic en SSH y luego en
.


Para clonar un repositorio mediante GitHub CLI, haz clic en GitHub CLI y, después, en
.







 


Abra Terminal.


Cambia el directorio de trabajo actual a la ubicación en donde quieres clonar el directorio.


Escriba git clone y pegue la dirección URL que ha copiado antes.

 git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY


Presione Entrar para crear el clon local.

 $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `Spoon-Knife`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.

b)checkout " seguido del nombre de la rama que queremos que sea la activa.
c)El comando git push te permite subir los commits desde tu rama (branch) local en tu repositorio git local al repositorio remoto.
Para poder subir a tu repositorio remoto, te debes asegurar de hacer commit  a todos tus cambios al repositorio local.
La sintaxis de ese comando es la siguiente:
git push <nombre del repositorio> <nombre de la rama>
Existen diferentes opciones que puedes pasar a este comando, puedes aprender más acerca de estos en la documentación de Git o ejecuta git push --help.
Subir a un repositorio remoto y rama específica.
En orden para subir tu código, primero debes clonar un repositorio a tu máquina local.
# Una vez clonado el repositorio, estarás trabajando dentro de la rama por defecto (Por defecto es `main`)
git clone https://github.com/<git-usuario>/<nombre-repo> && cd <nombre-repo>
# Haz cambios y agrega tus archivos (repite el comando `git add` por cada archivo, o utiliza `git add .` para agregarlos todos)
git add <nombre-archivo>
# Ahora haz el commit de tu código
git commit -m "Agregué cambios a mi repo!"
# Sube los cambios en la rama 'main' a github
git push origin main
Para aprender más acerca de ramas:
Git checkout
Git branch
Subir a un repositorio remoto específico y todas las ramas que contiene.
Si quieres subir todos tus cambios al repositorio remoto con todo y sus ramas, puedes utilizar:
git push --all <NOMBRE-REMOTO>
el cual:
--all es la bandera que señala que quieres subir todas las ramas al repositorio remoto.
NOMBRE-REMOTO es el nombre del repositorio remoto al cual las quieres subir.
Subir a una rama específica con el parámetro force
Si quieres ignorar los cambios locales hechos al repositorio Git en Github(Lo cual hacen la mayoría de desarrolladores para dar una solución rápida al servidor de desarrollo) luego puedes usar el comando —force para subir ignorando esos cambios.
git push --force <NOMBRE-REMOTO> <RAMA-REMOTA>
En la cual:
NOMBRE-REMOTO es el nombre del repositorio remoto al cual quieres subir los cambios.
RAMA-REMOTA es el nombre de la rama remota a la cual quieres subir los cambios.<br>
5-a)Trabajar con Remotos<br>
Para poder colaborar en cualquier proyecto Git, necesitas saber cómo gestionar repositorios remotos. Los repositorios remotos son versiones de tu proyecto que están hospedadas en Internet o en cualquier otra red. Puedes tener varios de ellos, y en cada uno tendrás generalmente permisos de solo lectura o de lectura y escritura. Colaborar con otras personas implica gestionar estos repositorios remotos enviando y trayendo datos de ellos cada vez que necesites compartir tu trabajo. Gestionar repositorios remotos incluye saber cómo añadir un repositorio remoto, eliminar los remotos que ya no son válidos, gestionar varias ramas remotas, definir si deben rastrearse o no y más. En esta sección, trataremos algunas de estas habilidades de gestión de remotos.
Ver Tus Remotos
Para ver los remotos que tienes configurados, debes ejecutar el comando git remote. Mostrará los nombres de cada uno de los remotos que tienes especificados. Si has clonado tu repositorio, deberías ver al menos origin (origen, en inglés) - este es el nombre que por defecto Git le da al servidor del que has clonado:
$ git clone https://github.com/schacon/ticgit
Cloning into 'ticgit'...
remote: Reusing existing pack: 1857, done.
remote: Total 1857 (delta 0), reused 0 (delta 0)
Receiving objects: 100% (1857/1857), 374.35 KiB | 268.00 KiB/s, done.
Resolving deltas: 100% (772/772), done.
Checking connectivity... done.
$ cd ticgit
$ git remote
origin
También puedes pasar la opción -v, la cual muestra las URLs que Git ha asociado al nombre y que serán usadas al leer y escribir en ese remoto:
$ git remote -v
origin	https://github.com/schacon/ticgit (fetch)
origin	https://github.com/schacon/ticgit (push)
Si tienes más de un remoto, el comando los listará todos. Por ejemplo, un repositorio con múltiples remotos para trabajar con distintos colaboradores podría verse de la siguiente manera.
$ cd grit
$ git remote -v
bakkdoor  https://github.com/bakkdoor/grit (fetch)
bakkdoor  https://github.com/bakkdoor/grit (push)
cho45     https://github.com/cho45/grit (fetch)
cho45     https://github.com/cho45/grit (push)
defunkt   https://github.com/defunkt/grit (fetch)
defunkt   https://github.com/defunkt/grit (push)
koke      git://github.com/koke/grit.git (fetch)
koke      git://github.com/koke/grit.git (push)
origin    git@github.com:mojombo/grit.git (fetch)
origin    git@github.com:mojombo/grit.git (push)
Esto significa que podemos traer contribuciones de cualquiera de estos usuarios fácilmente. Es posible que también tengamos permisos para enviar datos a algunos, aunque no podemos saberlo desde aquí.
Fíjate que estos remotos usan distintos protocolos; hablaremos sobre ello más adelante, en Configurando Git en un servidor.
Añadir Repositorios Remotos
En secciones anteriores hemos mencionado y dado alguna demostración de cómo añadir repositorios remotos. Ahora veremos explícitamente cómo hacerlo. Para añadir un remoto nuevo y asociarlo a un nombre que puedas referenciar fácilmente, ejecuta git remote add [nombre] [url]:
$ git remote
origin
$ git remote add pb https://github.com/paulboone/ticgit
$ git remote -v
origin	https://github.com/schacon/ticgit (fetch)
origin	https://github.com/schacon/ticgit (push)
pb	https://github.com/paulboone/ticgit (fetch)
pb	https://github.com/paulboone/ticgit (push)
A partir de ahora puedes usar el nombre pb en la línea de comandos en lugar de la URL entera. Por ejemplo, si quieres traer toda la información que tiene Paul pero tú aún no tienes en tu repositorio, puedes ejecutar git fetch pb:
$ git fetch pb
remote: Counting objects: 43, done.
remote: Compressing objects: 100% (36/36), done.
remote: Total 43 (delta 10), reused 31 (delta 5)
Unpacking objects: 100% (43/43), done.
From https://github.com/paulboone/ticgit
 * [new branch]      master     -> pb/master
 * [new branch]      ticgit     -> pb/ticgit
La rama maestra de Paul ahora es accesible localmente con el nombre pb/master - puedes combinarla con alguna de tus ramas, o puedes crear una rama local en ese punto si quieres inspeccionarla. (Hablaremos con más detalle acerca de qué son las ramas y cómo utilizarlas en [ch03-git-branching].)
Traer y Combinar Remotos
Como hemos visto hasta ahora, para obtener datos de tus proyectos remotos puedes ejecutar:
$ git fetch [remote-name]
El comando irá al proyecto remoto y se traerá todos los datos que aun no tienes de dicho remoto. Luego de hacer esto, tendrás referencias a todas las ramas del remoto, las cuales puedes combinar e inspeccionar cuando quieras.
Si clonas un repositorio, el comando de clonar automáticamente añade ese repositorio remoto con el nombre “origin”. Por lo tanto, git fetch origin se trae todo el trabajo nuevo que ha sido enviado a ese servidor desde que lo clonaste (o desde la última vez que trajiste datos). Es importante destacar que el comando git fetch solo trae datos a tu repositorio local - ni lo combina automáticamente con tu trabajo ni modifica el trabajo que llevas hecho. La combinación con tu trabajo debes hacerla manualmente cuando estés listo.
Si has configurado una rama para que rastree una rama remota (más información en la siguiente sección y en [ch03-git-branching]), puedes usar el comando git pull para traer y combinar automáticamente la rama remota con tu rama actual. Es posible que este sea un flujo de trabajo mucho más cómodo y fácil para ti; y por defecto, el comando git clone le indica automáticamente a tu rama maestra local que rastree la rama maestra remota (o como se llame la rama por defecto) del servidor del que has clonado. Generalmente, al ejecutar git pull traerás datos del servidor del que clonaste originalmente y se intentará combinar automáticamente la información con el código en el que estás trabajando.
Enviar a Tus Remotos
Cuando tienes un proyecto que quieres compartir, debes enviarlo a un servidor. El comando para hacerlo es simple: git push [nombre-remoto] [nombre-rama]. Si quieres enviar tu rama master a tu servidor origin (recuerda, clonar un repositorio establece esos nombres automáticamente), entonces puedes ejecutar el siguiente comando y se enviarán todos los commits que hayas hecho al servidor:
$ git push origin master
Este comando solo funciona si clonaste de un servidor sobre el que tienes permisos de escritura y si nadie más ha enviado datos por el medio. Si alguien más clona el mismo repositorio que tú y envía información antes que tú, tu envío será rechazado. Tendrás que traerte su trabajo y combinarlo con el tuyo antes de que puedas enviar datos al servidor. Para información más detallada sobre cómo enviar datos a servidores remotos, véase [ch03-git-branching].
Inspeccionar un Remoto
Si quieres ver más información acerca de un remoto en particular, puedes ejecutar el comando git remote show [nombre-remoto]. Si ejecutas el comando con un nombre en particular, como origin, verás algo como lo siguiente:
$ git remote show origin
* remote origin
  Fetch URL: https://github.com/schacon/ticgit
  Push  URL: https://github.com/schacon/ticgit
  HEAD branch: master
  Remote branches:
    master                               tracked
    dev-branch                           tracked
  Local branch configured for 'git pull':
    master merges with remote master
  Local ref configured for 'git push':
    master pushes to master (up to date)
El comando lista la URL del repositorio remoto y la información del rastreo de ramas. El comando te indica claramente que si estás en la rama maestra y ejecutas el comando git pull, automáticamente combinará la rama maestra remota con tu rama local, luego de haber traído toda la información de ella. También lista todas las referencias remotas de las que ha traído datos.
Ejemplos como este son los que te encontrarás normalmente. Sin embargo, si usas Git de forma más avanzada, puede que obtengas mucha más información de un git remote show:
$ git remote show origin
* remote origin
  URL: https://github.com/my-org/complex-project
  Fetch URL: https://github.com/my-org/complex-project
  Push  URL: https://github.com/my-org/complex-project
  HEAD branch: master
  Remote branches:
    master                           tracked
    dev-branch                       tracked
    markdown-strip                   tracked
    issue-43                         new (next fetch will store in remotes/origin)
    issue-45                         new (next fetch will store in remotes/origin)
    refs/remotes/origin/issue-11     stale (use 'git remote prune' to remove)
  Local branches configured for 'git pull':
    dev-branch merges with remote dev-branch
    master     merges with remote master
  Local refs configured for 'git push':
    dev-branch                     pushes to dev-branch                     (up to date)
    markdown-strip                 pushes to markdown-strip                 (up to date)
    master                         pushes to master                         (up to date)
Este comando te indica a cuál rama enviarás información automáticamente cada vez que ejecutas git push, dependiendo de la rama en la que estés. También te muestra cuáles ramas remotas no tienes aún, cuáles ramas remotas tienes que han sido eliminadas del servidor, y varias ramas que serán combinadas automáticamente cuando ejecutes git pull.
Eliminar y Renombrar Remotos
Si quieres cambiar el nombre de la referencia de un remoto puedes ejecutar git remote rename. Por ejemplo, si quieres cambiar el nombre de pb a paul, puedes hacerlo con git remote rename:
$ git remote rename pb paul
$ git remote
origin
paul
Es importante destacar que al hacer esto también cambias el nombre de las ramas remotas. Por lo tanto, lo que antes estaba referenciado como pb/master ahora lo está como paul/master.
Si por alguna razón quieres eliminar un remoto - has cambiado de servidor o no quieres seguir utilizando un mirror o quizás un colaborador ha dejado de trabajar en el proyecto - puedes usar git remote rm:
$ git remote rm paul
$ git remote
origin
b)En una solicitud de incorporación de cambios, puedes revisar y opinar sobre las confirmaciones, los archivos cambiados y las diferencias (o "diff") entre los archivos de las ramas base y comparada.
CodespacesWeb browser
Acerca de revisar solicitudes de extracción
Puedes revisar los cambios de una solicitud de extracción en un archivo por vez. Mientras revisas los archivos en una solicitud de extracción, puedes dejar comentarios individuales en cambios específicos. Después de que terminas de revisar cada archivo, puedes marcarlo como visto. Esto colapsa el archivo, lo cual te ayuda a identificar los archivos que aún debes revisar. Una barra de progreso en el encabezado de la solicitud de cambios muestra la cantidad de archivos que has visto. Después de revisar tantos archivos como quieras, puedes aprobar la solicitud de cambios o solicitar cambios adicionales si emites tu revisión con un comentario de resumen.
Propina: Puedes encontrar una solicitud de incorporación de cambios en la que se te solicite a ti o a un equipo del que formes parte una revisión con el calificador de búsqueda review-requested:[USERNAME] o team-review-requested:[TEAMNAME]. Para obtener más información, vea «Buscar propuestas y solicitudes de extracción».
Comenzar una revisión
En el nombre del repositorio, haga clic en  Solicitudes de incorporación de cambios.

En la lista de solicitudes de incorporación de cambios, haga clic en la que quiera revisar.
En la solicitud de incorporación de cambios, haz clic en  Archivos cambiados.

Puedes cambiar el formato de la vista de diferencias en esta pestaña si haces clic en  y eliges la vista unificada o dividida. La elección que hagas aplicará cuando veas el diff para otras solicitudes de cambio.

También puedes elegir esconder las diferencias de espacios en blanco. La elección que hagas solo aplicará a esta solicitud de cambios y se recordará la siguiente ocasión que visites la página.
Opcionalmente, filtra los archivos para mostrar solo aquellos que quieras revisar o utiliza el árbol de archivos para ir a uno en concreto. Para obtener más información, vea «Filtrar archivos en una solicitud de extracción».
Mantén el puntero sobre la línea de código donde quieres agregar un comentario y haz clic en el icono de comentario azul. Para agregar un comentario en varias líneas, haz clic y arrastra para seleccionar el intervalo de líneas y, luego, haz clic en el icono de comentario azul.

Teclea tu comentario en el campo de comentario.
Opcionalmente, para sugerir un cambio específico en una o varias líneas, haz clic en  y, luego, edita el texto dentro del bloque de sugerencias.

Para comentar directamente un archivo, a la derecha de este, haz clic en  y escribe el comentario.

Cuando haya terminado, haga clic en Iniciar una revisión. Si ya ha iniciado una revisión, puede hacer clic en Agregar comentario de revisión.
Antes de enviar la revisión, los comentarios de líneas están pendientes y solo los puede ver usted. Puedes editar los comentarios pendientes en cualquier momento antes de enviar tu revisión. Para cancelar una revisión pendiente, incluidos todos sus comentarios pendientes, haz clic en Revisar cambios encima del código modificado y, luego, haz clic en Cancelar revisión.

Revisar los cambios de las dependencias
Si la solicitud de cambios contiene cambios para las dependencias, puedes utilizar la revisión de dependencias para un archivo de bloqueo o de manifiesto para ver qué ha cambiado y verificar si los cambios introducen vulnerabilidades de seguridad. Para obtener más información, vea «Revisar los cambios de las dependencias en una solicitud de cambios».
En la solicitud de incorporación de cambios, haz clic en  Archivos cambiados.

A la derecha del encabezado de un archivo de bloqueo o de manifiesto, haga clic en el botón de diferencias enriquecidas  para mostrar la revisión de dependencias.

Puede que también quieras revisar el diff origen, ya que podría haber cambios en el archivo de bloqueo o de manifiesto que no cambian de dependencia o podrían haber dependencias que GitHub no puede procesar, las cuales, como resultado, no aparecen en la revisión de dependencias.
Para regresar a la vista de diferencias de origen, haz clic en el botón  .

Marcar un archivo como visto
Después de que hayas terminado de revisar un archivo, puedes marcar el archivo como visto, y el archivo se colapsará. Si el archivo se modifica después de que lo hayas visto, dejará de estar marcado como visto.
En la solicitud de incorporación de cambios, haz clic en  Archivos cambiados.

A la derecha del encabezado del archivo que ha terminado de revisar, seleccione Visto.

Enviar tu revisión
Después de que hayas terminado de revisar todos los archivos que quieras de la solicitud de extracción, envía tu revisión.
En la solicitud de incorporación de cambios, haz clic en  Archivos cambiados.

Encima del código cambiado, haga clic en Revisar cambios.

Teclea un comentario que resuma tu retroalimentación sobre los cambios propuestos.
Selecciona el tipo de revisión que te gustaría proporcionar:
Seleccione Comentario para dejar un comentario general sin aprobar de manera explícita los cambios ni solicitar cambios adicionales.
Seleccione Aprobar para enviar los comentarios y aprobar la combinación de los cambios propuestos en la solicitud de incorporación de cambios.
Seleccione Solicitar cambios para enviar comentarios que se deben abordar antes de que se pueda combinar la solicitud de incorporación de cambios.
Haga clic en Enviar revisión.
v





