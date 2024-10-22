
# Rock-Paper-Scissors NFT Tapp Game Concept

## 1. Overview:
This game is a 5-minute round of Rock-Paper-Scissors, where each match is an NFT Tapp owned by the creator (referred to as the "Owner"). The Owner can share the Tlink for this game via their Twitter, inviting their followers to play. Players participate by selecting one of the three moves: rock, paper, or scissors, with the cost of $1 per move. Additionally, players have a "Share to Earn" option, where they can share the game with their own networks.

## 2. Key Features:
- **NFT Tapp Ownership:** 
  - Each round of the game is represented by an NFT, and the person who initiates the game is the Owner of that NFT Tapp. 
  - Owners can earn a percentage of the game revenue through platform fees and interaction fees.

- **Tlink Sharing:** 
  - The NFT Owner can generate a Tlink (TokenScript link) that they share on Twitter to invite followers to play. The Tlink will bring players directly into the game, creating seamless engagement from Twitter.

- **Gameplay Mechanics:**
  - **Four Buttons/Cards:** There are four buttons available for players:
    1. **Rock**
    2. **Paper**
    3. **Scissors**
    4. **Share to Earn**
  - Players choose between Rock, Paper, and Scissors, with each selection costing $1. The system will randomly match players against one another.
  - Players can also choose to share the game on their own Twitter account via the "Share to Earn" button to earn bonuses or invite more participants.

- **Random Matching & Single Player Pool:**
  - Players are randomly matched against other players who are in the same game round. If an odd number of players participate, the unpaired player forfeits their move fee to the NFT Tapp Owner.
  
- **Settlement:**
  - Every 5 minutes, the game round ends, and the results are announced by **@tBot** on Twitter, which will post the outcomes of the match.
  
- **Leaderboard:**
  - The game will feature a **Leaderboard** where top players with the most wins will be displayed, encouraging competitive play.

## 3. Revenue and Fees:
- **10% Transaction Fee:**
  - Every time a player makes a selection (Rock, Paper, or Scissors), a 10% fee is charged on the $1 they spent.
  - **9%** of the fee is sent to the Owner of the NFT Tapp.
  - **1%** goes to the platform hosting the game (SLN mainnet or Tapp platform).
  
## 4. User Flow:
1. **Owner Starts a Game:** 
   - The Owner initiates a new game round, creating an NFT Tapp.
   - They can then share the Tlink via Twitter to invite players.
   
2. **Players Join the Game:**
   - Followers or anyone who clicks the Tlink can participate by selecting their move (Rock, Paper, or Scissors) for $1.
   - Players are randomly matched.

3. **Result Announcement:**
   - After 5 minutes, @tBot posts the results of the match on Twitter.
   
4. **Fee Distribution:**
   - Transaction fees are automatically distributed: 9% to the Owner and 1% to the platform.

5. **Leaderboard Update:**
   - The leaderboard updates in real-time based on player wins.

## Technical Considerations for Development:
1. **NFT Minting:** Each game round is minted as an NFT, making it a unique digital asset owned by the round creator.
2. **TokenScript Integration:** Use TokenScript to enable smart contracts that manage the game mechanics, handle transactions, and facilitate seamless Twitter-Tlink sharing.
3. **@tBot Integration:** A bot automatically announces game results on Twitter after each 5-minute round.
4. **Random Matchmaking:** Smart contracts should handle random matchmaking between players.
5. **Revenue Split:** Ensure smart contract logic distributes fees between NFT Owner and platform.
