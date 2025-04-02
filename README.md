# GD Starsign driver

Para conseguir usar o token no linux, siga os seguintes passos:

1. Faça o download do arquivo gd_starsign_install.sh (click on file > Download Raw File)
2. Abra a janela do terminal (Ctrl + Alt + T)
3. Copie e cole os seguintes comandos:

```bash
cd Downloads &&
sudo chmod a+x gd_starsign_install.sh &&
./gd_starsign_install.sh
```

Vá confirmando as instalações usando suas senhas, caso apareça a necessidade de instalar libs que não estão presentes no ubuntu, segue a lista das mesmas:

https://pkgs.org/download/libtiff5
https://pkgs.org/download/libssl1.1
https://pkgs.org/download/libwxbase3.0-0v5
https://pkgs.org/download/libwxgtk3.0-gtk3-0v5

Escolha a versão dos seus dispositivos, no caso do ubuntu 24, sempre opte pela versão do ubuntu mais recente, como a 22 ou a 20. Ao selecionar a versão, vai abrir a pasta de download é só baixar as libs, e instalar:

```bash
sudo dpkg -i <NOME_DO_ARQUIVO>
```

após instalar tudo que falta, basta rodar novamente

```bash
./gd_starsign_install.sh
```