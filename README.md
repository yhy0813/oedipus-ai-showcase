# 《俄狄浦斯王》AI剧情交互系统｜更新版网页展示页

## 更新内容

- Module 04 改为：神谕符文 → 剧情状态机
- Module 05 改为：记忆回溯 → 连续回应
- 交互热点调整为：角色、NPC、背景雷电、地面符文、人物头部、权杖
- 背景图使用带地面符文的纯场景图
- 视频弹窗取消自动播放，点击播放更稳定

## 视频文件名

请把 6 个视频放入 `videos` 文件夹，并按以下文件名命名：

1. `01_explore_to_interaction.mp4`
2. `02_free_input_ai_parse.mp4`
3. `03_parameter_scene_feedback.mp4`
4. `04_oracle_plot_state_machine.mp4`
5. `05_memory_recall_continuity.mp4`
6. `06_truth_confrontation_battle.mp4`

如果你沿用旧文件名，请修改 `app.js` 中对应模块的 `video` 字段。

## 本地预览

双击 `index.html` 即可。

若样式未更新，请在浏览器中按 `Command + Shift + R` 强制刷新。

## 调整点击热区

在 `styles.css` 中修改：

- `.player`
- `.npc`
- `.lightning`
- `.oracle`
- `.head`
- `.staff`


## Final 版更新

- 删除左侧大型“系统功能导航”面板，减少画面遮挡。
- 功能说明改为鼠标悬停热点时弹出的详情提示。
- 人物头部 / 大脑热点位置已微调。
- 视频文件名未更改，仍保持 v2 中的命名规则。
