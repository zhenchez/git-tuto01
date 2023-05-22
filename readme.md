#### La otra otra parte de la documentación está aquí: [1.1 - 1.3](https://docs.google.com/document/d/1j715m4wy40CDnWMW1mSkL1gjkGmKwpmDfacgsDqzjW4/edit?usp=sharing "Documentación anterior")

># 1.4 - Intenta subir los ficheros al repositorio remoto mediante el comando git push ¿Se te ocurre qué está pasando? 
>>En un principio no podemos subir los ficheros a ningún repositorio remoto ya que no hemos vinculado ningúno. ❌

***

># 1.5 - Ejecuta el comando git remote -v e investiga porque no nos aparece nada.
>> Ejecutamos el comando **git remote -v**.
>>![F imagen](https://i.gyazo.com/3ae78ec43130a7c330af3e419ae2a253.png "Ejecución del comando git remote-v")

***

># 1.6 - Crea un repositorio remoto llamado repo01, asócialo a tu repositorio local.
>>* Nos vamos a dirigir a **GitHub** y crearemos un nuevo repositorio.  
>>* ![F imagen](https://i.gyazo.com/f01a1f5566d01e480f10d50cd7825384.png "Nuevo repositorio creado")
>>* Ahora es hora de asociarlo a nuestro repositorio local usando las siguientes líneas:
>>*  ![F imagen](https://i.gyazo.com/41c8a80af97d263fa3dd0f257a635bb8.png "Líneas para asociar repositorio")
>>* Finalmente podremos ver que este archivo "readme.md" se encuentra en nuestro repositorio remoto.
>>* ![F imagen](https://i.gyazo.com/234a43d32af757534d84d2dc703a00b1.png "Líneas para asociar repositorio")

***

># 1.7 - Vuelve a ejecutar el comando git remote -v nuevamente y explica el porque ahora si que aparece.
>>Ejecutamos de nuevo el comando **git remote -v** y veremos que ya nos aparece nuestro repositorio en remoto.
>>![F imagen](https://i.gyazo.com/8db44823c2ff7409a07824274c616aba.png "Líneas para asociar repositorio")
>>* Ahora nos aparece ya que hemos vinculado el repositorio local al remoto.

***

># 1.8 - Sube los cambios que hemos subido al snapshot local (commit) hacía al repositorio remoto.
>>* Primero vamos a añadir los archivos del repositorio local a la **stage area** usando un **git add readme.md** o si tenemos más de un archivo y los queremos subir todos un **git add .**.
>>* Por siguiente tend

***

># 1.9 - Ves al repositorio remoto (en este caso GitHub) y comprueba que se haya realizado el commit correctamente y observa que pasa en el repositorio ¿Observas algo peculiar?
>>