-- By yJoh --

-- Instances:

local Hack = Instance.new("ScreenGui")
local Frame = Instance.new("ImageLabel")
local TextButton_Roundify_12px = Instance.new("ImageLabel")
local on = Instance.new("TextButton")
local TextButton_Roundify_12px_2 = Instance.new("ImageLabel")
local off = Instance.new("TextButton")
local main = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")

--Properties:

Hack.Name = "Hack"
Hack.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Name = "Frame"
Frame.Parent = Hack
Frame.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
Frame.BackgroundTransparency = 1.000
Frame.BorderColor3 = Color3.fromRGB(109, 109, 109)
Frame.Position = UDim2.new(0.688340843, 0, 0.714102566, 0)
Frame.Size = UDim2.new(0, 220, 0, 203)
Frame.Image = "rbxassetid://3570695787"
Frame.ImageColor3 = Color3.fromRGB(47, 47, 47)
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.120

TextButton_Roundify_12px.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px.Parent = Frame
TextButton_Roundify_12px.Active = true
TextButton_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px.BackgroundTransparency = 1.000
TextButton_Roundify_12px.Position = UDim2.new(0.499999732, 0, 0.473645449, 0)
TextButton_Roundify_12px.Selectable = true
TextButton_Roundify_12px.Size = UDim2.new(0.660000026, 0, 0.19556655, 0)
TextButton_Roundify_12px.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px.ImageColor3 = Color3.fromRGB(77, 77, 77)
TextButton_Roundify_12px.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px.SliceScale = 0.120

on.Name = "on"
on.Parent = TextButton_Roundify_12px
on.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
on.BackgroundTransparency = 1.000
on.BorderColor3 = Color3.fromRGB(255, 255, 255)
on.BorderSizePixel = 0
on.Position = UDim2.new(-0.181818157, 0, -0.133203357, 0)
on.Size = UDim2.new(0, 202, 0, 50)
on.Font = Enum.Font.Unknown
on.Text = "On"
on.TextColor3 = Color3.fromRGB(2, 138, 0)
on.TextSize = 18.000

TextButton_Roundify_12px_2.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_2.Parent = Frame
TextButton_Roundify_12px_2.Active = true
TextButton_Roundify_12px_2.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_2.BackgroundTransparency = 1.000
TextButton_Roundify_12px_2.Position = UDim2.new(0.499999732, 0, 0.739655256, 0)
TextButton_Roundify_12px_2.Selectable = true
TextButton_Roundify_12px_2.Size = UDim2.new(0.660000026, 0, 0.19556655, 0)
TextButton_Roundify_12px_2.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_2.ImageColor3 = Color3.fromRGB(77, 77, 77)
TextButton_Roundify_12px_2.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_2.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_2.SliceScale = 0.120

off.Name = "off"
off.Parent = TextButton_Roundify_12px_2
off.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
off.BackgroundTransparency = 1.000
off.BorderColor3 = Color3.fromRGB(255, 255, 255)
off.BorderSizePixel = 0
off.Position = UDim2.new(-0.181818157, 0, -0.133203357, 0)
off.Size = UDim2.new(0, 202, 0, 50)
off.Font = Enum.Font.Unknown
off.Text = "Off"
off.TextColor3 = Color3.fromRGB(211, 0, 7)
off.TextSize = 18.000
off.TextWrapped = true

main.Name = "main"
main.Parent = Frame
main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
main.BackgroundTransparency = 1.000
main.Position = UDim2.new(0.0454545468, 0, 0.0394088663, 0)
main.Size = UDim2.new(0, 202, 0, 37)
main.Image = "rbxassetid://3570695787"
main.ImageColor3 = Color3.fromRGB(77, 77, 77)
main.ScaleType = Enum.ScaleType.Slice
main.SliceCenter = Rect.new(100, 100, 100, 100)
main.SliceScale = 0.120

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.00495049497, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 37)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "By yJoh"
TextLabel.TextColor3 = Color3.fromRGB(15, 15, 15)
TextLabel.TextSize = 17.000

-- Scripts:

local function WUHGP_fake_script() -- on.LocalScript 
	local script = Instance.new('LocalScript', on)

	on.MouseButton1Down:connect(function()
	_G.toggled = true
	while _G.toggled == true do
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-42.1867104, 4, -10.0159426)
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(51.8459854, 4, -7.64399719)
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(49.0132484, 4, 12.9164495)
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-49.2372742, 10.0727692, 22.5755386)
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(22.6320515, 15.2083225, -22.8036976)
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(54.5018234, 4, 12.9243202)
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-50.9209137, 4, 23.7264462)
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-51.7601433, 9.02024555, 24.8675385)
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(54, 4, 3)
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-45.7298431, 4, 14.7902403)
		wait(0.25)
	end
	end)
end
coroutine.wrap(WUHGP_fake_script)()
local function ZZDR_fake_script() -- off.LocalScript 
	local script = Instance.new('LocalScript', off)

	off.MouseButton1Down:connect(function()
		_G.toggled = false
	end)
end
coroutine.wrap(ZZDR_fake_script)()
