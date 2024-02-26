# Decentralized Voting Application

## Installation

After you clone the repository, you should install the packages using

```shell
npm install
```

You first need to compile the contract and deploy it to the blockchain network (The one I used is called Volta).
Run the following commands to compile and upload the contract.

```shell
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. You can also use another blockchain by writing the blockchain's endpoint in hardhat-config.

Add your private key, API URL and Contract address in your .env file, then paste the contract address and ABI in your constant.js file
then simply run this command.

```shell
npm start
```
