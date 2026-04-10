# IT-5104N-GAME-DEVELOPMENT

Week 1
2D project

Week 2 : Activity 1
Gameplay Mechanics
Subtopics: Handling input (keyboard/gamepad), physics bodies (rigid/kinematic), collision detection. Basics of player controllers (movement, jumping).
Exercises: Build a dodge mechanic or simple platformer character; test with physics tweaks.
Links:


Week 3: Activity1 UI/UX & Audio
Subtopics:
      HUD elements (health bars, scores), menu systems (CanvasLayer), audio
      buses for mixing SFX/music.
Exercises:
      Integrate UI into your game proto; add sound effects, walk, run, slash, etc. You may also add game music, introduction, and so on.
Links:
      GUI in Godot | Audio Features | Audacity Guide.


Week 3 Activity 2 AI & Enemies
Subtopics:
      Pathfinding navigation, finite state machines for behaviors
      (patrol/attack), enemy AI patterns.
Exercises:
      Add enemies to your game (note enemies, not obstacles)
Links:
      Navigation and Pathfinding | State
      Machines | AI Behaviors Tutorial.



Week 4 Activity 1 :3D Basics & Optimization
Subtopics:
      3D nodes (meshes, cameras), lighting (DirectionalLight), profiling tools
      for FPS optimization.
Exercises:
      Convert your 2D proto to 3D; optimize for 60 FPS.
Links:
      3D Introduction | Optimization Techniques | Lighting Tutorial.

Github link - 3d game: https://github.com/zechariahjose/3D_GameDev.git




Week 4 Activity 1 Multiplayer (basic cloud server)    

Manuel's Notes : 
You can try both the cloud based or the local network based, but I only need 1 either cloud or local.
if you cannot complete by Friday, please continue this on Saturday, I think this will be a bit challenging.

Details : 
Nakama client setup, authentication, matchmaking & relayed realtime sync. 
Add basic 2-player movement sync to an existing prototype (e.g., top-down shooter or platformer); commit with working join/match demo.    Multiplayer (basic cloud server)
o Subtopics: Installing Nakama Godot SDK, connecting to Heroic Cloud or local Nakama server (Docker quick-start), device/email authentication, creating/joining matches via matchmaking or code, using Nakama's relayed multiplayer (socket + match messages), syncing player position/inputs with MultiplayerSynchronizer or manual RPC-like messages via Nakama.
o Exercises:

Set up Nakama Godot addon (from AssetLib or GitHub release) and connect to a free Heroic Cloud instance or local Docker Nakama (use official quick-start guide).
Implement basic authentication (device ID or email/password).
Add a simple lobby/matchmaking screen (create match or join random).
Take one previous prototype (e.g., top-down shooter or platformer player controller). Sync at least player position and basic actions (move/jump/shoot) between 2 clients in realtime using Nakama match data/messages.
Test with 2 Godot instances on the same network or via cloud (playtest movement sync, handle disconnects gracefully). Commit code + short video/gif of 2 players moving together.    Rubric
Correct Nakama connection & auth → 0–3 pts
Successful matchmaking/join → 0–3 pts
Realtime player sync (position/actions) → 0–3 pts
Clean code, error handling & demo video → 0–1 pt

