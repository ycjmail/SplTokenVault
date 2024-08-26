* * *


This repository is from [Solana Playground](https://beta.solpg.io/tutorials/spl-token-vault): . I updated it from Anchor 0.29.0 to Anchor 0.30.1 and corrected some errors.



* * *


test anchor command: 

```
yarn 
avm install 0.30.1
avm use 0.30.1
anchor keys sync
anchor build 
anchor test 
```


* * *



test client in localnet command:
```
yarn 
solana-test-validator --bpf-program metaqbxxUerdq28cj1RbAWkYQm3ybzjb6a8bt518x1s DIR_OF_token_metadata/token_metadata.so 
anchor deploy
anchor run client 
```
