# R_projet

Il s'agit d'une mission R de Romane, Clément, Zihao.

## !!! Étapes nécessaires à l'utilisation !!! 

1. Cloner
  - [ ] git clone # <Première fois seulement>
  ```bash
  $ git clone https://github.com/zeio99/R_projet.git
  $ cd R_projet
  ```
  - [ ] Mises à jour
  ```bash
  $ git pull
  $ git check dev # <Zone de travail>
  ```
  
2. Soumettre # <Attention>
  ```bash
  $ git add .
  $ git commit -m "AAAA" # AAAA comme note, par exemple la date...
  $ git push -u origin dev # <Zone de travail>
  ```




git push -u origin 分支名
  
  
  
  
  
  - [X] Totally remove g2o to get rid of the tons annoying Warnings
  - [X] cv::Mat for matrix to be remove
  - [X] Fix CeresOptimizer, sometimes get "Matrix not positive definite" warning
  - [X] Fix Relocalization, sometimes may get stuck
  - [X] Fix LocalBundleAdjustment with add inv sigma to error calculation
  - [ ] EssentialGraph in CeresOptimizer need to fix
  - [ ] Reconstruct to make code modular, at least make feature matcher as an independent module
  - [ ] Add IMU data to get scale information
  - [ ] Add map save for map reusing
