# AudiorepML

A quantidade de atividades realizadas via videoconferência explodiu com a necessidade de permanecer em casa. Com isso, metodos e algoritmos de compressão de audio são empregados para diminuir a carga nos servidores e na rede em si. Porém, essas compressões diminuem drasticamente a qualidade do áudio sendo transmitido, diminuindo a experiência de todos na conferência. 

O projeto busca melhorar a experiência dos usuários, melhorando a qualidade do áudio recebido por meio de técnicas de aprendizado de máquina.

Como áudios base serão utilizados podcasts em português, com apresentadores masculinos e femininos.

Esses áudios serão reduzidos a diversas qualidades pelos meios de compressão atuais e, por meio de uma RNN encoder-decoder, essas compressões serão restauradas para níveis dos arquivos originais