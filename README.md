local Rayfield = loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/LOL/main/README.md"))()

local Window =
    Rayfield:CreateWindow(
    {
        Name = "FRITE/C.N HUB",
        LoadingTitle = "Best Gui",
        LoadingSubtitle = "C.N/FRITE on yt",
        ConfigurationSaving = {
            Enabled = false,
            FolderName = nil, -- Create a custom folder for your hub/game
            FileName = "Example Hub"
        },
        Discord = {
            Enabled = false,
            Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
            RememberJoins = true -- Set this to false to make them join the discord every time they load it up
        },
        KeySystem = false, -- Set this to true to use our key system
        KeySettings = {
            Title = "Key | FRITE/C.N on Top",
            Subtitle = "Key System",
            Note = "Key is espace",
            FileName = "YoutubeHubKey1", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
            SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
            GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
            Key = {""} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
        }
    }
)

local MainTab = Window:CreateTab("GUIS", nil) -- Title, Image

local MainSection = MainTab:CreateSection("Main")

local Tab = Window:CreateTab("PVP", nil)

local Section = Tab:CreateSection("PvP")

local ScriptTab = Window:CreateTab("Script", nil)

local section = ScriptTab:CreateSection("Script")


Rayfield:Notify(
    {
        Title = "You executed the script",
        Content = "FRITE/C.N on top",
        Duration = 5,
        Image = nil,
        Actions = {
            Ignore = {
                Name = "Okay!",
                Callback = function()
                    print("The user tapped Okay!")
                end
            }
        }
    }
)

local Button =
    MainTab:CreateButton(
    {
        Name = "x1",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/x1/main/README.md"))()
        end
    }
)


local Button =
    MainTab:CreateButton(
    {
        Name = "x2",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/x2/main/README.md"))()
        end
    }
)


local Button =
    MainTab:CreateButton(
    {
        Name = "x3",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/x3/main/README.md"))()
        end
    }
)


local Button =
    MainTab:CreateButton(
    {
        Name = "x4",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/x4/main/README.md"))()
        end
    }
)


local Button =
    MainTab:CreateButton(
    {
        Name = "x5",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/x5/main/README.md"))()
        end
    }
)


local Button =
    MainTab:CreateButton(
    {
        Name = "x6",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/x6/main/README.md"))()
        end
    }
)


local Button =
    MainTab:CreateButton(
    {
        Name = "x7",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/x7/main/README.md"))()
        end
    }
)


local Button =
    MainTab:CreateButton(
    {
        Name = "x8",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/x8/main/README.md"))()
        end
    }
)


local Button =
    MainTab:CreateButton(
    {
        Name = "x9",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/x9/main/README.md"))()
        end
    }
)


local Button =
    MainTab:CreateButton(
    {
        Name = "x10",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/x10/main/README.md"))()
        end
    }
)

local Button =
    MainTab:CreateButton(
    {
        Name = "kill boss pouple",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/kill-boss-pouple/main/README.md"))()
        end
    }
)

local Button =
    MainTab:CreateButton(
    {
        Name = "kill boss requin",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/kill-boss-requin/main/README.md"))()
        end
    }
)

local Button =
    MainTab:CreateButton(
    {
        Name = "kill boss crocodile",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/kill-boss-crocodile/main/README.md"))()
        end
    }
)

local Button =
    MainTab:CreateButton(
    {
        Name = "kill boss tortue",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/kill-boss-tortue/main/README.md"))()
        end
    }
)

local Button =
    MainTab:CreateButton(
    {
        Name = "10k per sec (heart)",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/10k-per-sec-heart-/main/README.md"))()
        end
    }
)

local Button =
    MainTab:CreateButton(
    {
        Name = "Anti afk",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/anti-afk/main/Anti%20afk"))()
        end
    }
    )

   
local Button =
    Tab:CreateButton(
    {
            Name = "Kill Aura",
            Callback = function()
                loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/kill-aura/main/README.md"))()
            end

    }
    )
    
    local Button =
    Tab:CreateButton(
    {
            Name = "Hitbox",
            Callback = function()
                loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/hitbox-all-game/main/hitbox"))()
            end

    }
    )
    

local Slider = Tab:CreateSlider(
    {
            Name = "Speed",
            Range = {16, 250},
            Increment = 10,
            Suffix = "Ws",
            CurrentValue = 10,
            Flag = "Slider1",
            Callback = function(v)
                game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = v
            end,
    }
    )

    local Slider = Tab:CreateSlider(
        {
                Name = "JumpPower",
                Range = {50, 500},
                Increment = 10,
                Suffix = "JumpPower",
                CurrentValue = 10,
                Flag = "Slider1",
                Callback = function(v)
                    game.Players.LocalPlayer.Character.Humanoid.JumpPower = v
                end,
        }
        )
    

local Button =
ScriptTab:CreateButton(
    {
        Name = "Infinite yeild",
        Callback = function()
            loadstring(game:HttpGet("  https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
        end
    }
)

local Button = 
ScriptTab:CreateButton(
    {
        Name = "Keybord For mobile",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
        end
    }
)

local Button = 
Tab:CreateButton(
    {
        Name = "kill all on fire blue",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/kill-all-uw/main/kill%20all%20on%20fire"))()
        end
    }

)

local Button = 
ScriptTab:CreateButton(
    {
        Name = "low detail",
        Callback = function()
            loadstring(game:HttpGet("https://pastebin.com/raw/uXA9zP76", true))()
        end
    }
)
local Button =
    ScriptTab:CreateButton(
    {
        Name = "RTX",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/script-RTX/main/RTX"))()
        end
    }
)

local Button =
    ScriptTab:CreateButton(
    {
        Name = "Simple",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/78n/SimpleSpy/main/SimpleSpySource.lua"))()
        end
    }
)

local Button =
    ScriptTab:CreateButton(
        {
            Name = "Reset",
            Callback = function()
                loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/Reset-for-kill/main/README.md"))()
            end
    }
)

local Button = 
    ScriptTab:CreateButton(
        {
            Name = "kill for tile AS",
            Callback = function()
                loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/kill-for-AS/main/README.md"))()
            end
        }
    )

local Button = 
    ScriptTab:CreateButton(
        {
            Name = "Reset coin forAS",
            Callback = function()
                loadstring(game:HttpGeet("https://raw.githubusercontent.com/xpzrmodzz/Reset-for-coins-/main/README.md"))()
            end
        }
     
    )

Rayfield:LoadConfiguration()
