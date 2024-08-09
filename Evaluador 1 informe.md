***Informe de Evaluaciòn: Ataque de Ransomware***

***Introducción***
    
    Por medio de este informe documenta los resultados de una evaluación exhaustiva de las defensas contra malware implementadas en un entorno de prueba simulado. El objetivo principal de esta evaluación fue evaluar la eficacia de las herramientas de seguridad utilizadas y identificar áreas de mejora.

***Metodología***

*Entorno de Prueba:*

Sistema Operativo: Windows 10

*Herramientas:*
 Windows Defender, Malwarebytes, ClamAV, Cuckoo Sandbox.

*Malware:*

 Ransomware Teslacrypt 2 detectado.

***Procedimiento:***

Instalación y Configuración: Se instalaron y configuraron las herramientas de seguridad en el sistema operativo, de acuerdo a lo sugerido por los desarrolladores.


*Métricas:*

 Se calcularon las siguientes métricas: tasa de detección, tasa de falsos positivos, tiempo de detección y tiempo de respuesta.

***Resultados***

Tabla Comparativa de Herramientas

Análisis Detallado
Bitdefender: Demostró una buena capacidad de detección general, especialmente para malware común. Sin embargo, presentó dificultades en la detección de algunas variantes de ransomware y exploits de día cero.
Malwarebytes: Ofreció la tasa de detección más alta y el tiempo de respuesta más rápido, destacándose en la detección de amenazas emergentes.
ClamAV: Si bien presentó una tasa de falsos positivos baja, su tasa de detección fue inferior a las otras herramientas, especialmente para malware más sofisticado.

Análisis de Sandbox

El análisis en el sandbox reveló que el Ramsonware utilizado consiguió:
Modificar el registro: Para persistir en el sistema y evitar la eliminación.
Crear archivos ocultos: Para almacenar componentes maliciosos y evadir la detección.
Establecer conexiones de red: Para comunicarse con un servidor de comando y controlde forma remota.

Gráfico de Tiempo de Detección


***Conclusiones***

Bitdefender se destacó como la herramienta más efectiva en términos de tasa de detección y tiempo de respuesta.

TROJAN KILLER (ANTIVIRUS) tiene su versión portable para pen.
https://trojan-killer.com/

MALWAREBYTES (ANTIVIRUS)  podes bajar una version gratuita para usuarios comunes.
https://es.malwarebytes.com/


Recomendaciones
Uso de Shadow explorer desde una unidad USB para buscar los archivos que se puedan recuperar que elude la infeccion del virus. También servirá para bloquear los puntos de restauraciòn anteriores
https://www.myantispyware.com/download/shadowexplorer/#google_vignette


Uso de un desencriptador de archivos EMSISOFT Decriptor
https://www.emsisoft.com/en/blog/34375/emsisoft-releases-new-decryptor-for-stop-djvu-ransomware/

Tambièn es utili la instalacion de la extension de Bitdefender (en caso de ser Grand Crab)
https://www.bitdefender.com/blog/labs/gandcrab-ransomware-decryption-tool-available-for-free/
Combinación de Herramientas: Utilizar una combinación de herramientas de seguridad para mejorar la protección.

Actualizaciones Regulares: Mantener las firmas de malware y las definiciones de amenazas actualizadas.

***Análisis de Comportamiento:***
Implementar soluciones de análisis de comportamiento para detectar amenazas desconocidas.
Educación de los Usuarios: Capacitar a los usuarios sobre las mejores prácticas de seguridad para evitar infecciones.
Pruebas de Penetración: Realizar pruebas de penetración periódicas para identificar vulnerabilidades.
Anexos

Logs detallados de las herramientas de seguridad
Reportes del sandbox
Capturas de pantalla 

Se realizó anàlisis de Scripts de malware utilizados

***Consideraciones Adicionales:***

Al comenzar a implementar una nueva instalaciòn de disco duro, y sistema operativo se han de considerar las sisguientes medidas de seguridad. 
Análisis de Riesgos: un escaneo de redes para verificar posibles amenazas del entorno y la eliminación de este tipo de riesgos. 


Incident Response: 
Instalaciòn de un antivirus de firma 
Instalaciòn de un antivirus heurístico 

Compliance: las medidas de seguridad deben estar acorde a un marco operativo NIST CSF

