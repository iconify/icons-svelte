<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/kbx02gbvp.css';
import '../../css/v/vu5vvzbot.css';
import '../../css/y/yrdr5wbbm.css';
import '../../css/q/qu1_sqbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="kbx02gbvp wm-deco"/><path class="vu5vvzbot wm-deco"/><path class="wm-k yrdr5wbbm"/><path class="qu1_sqbpg wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rectangle-ellipsis-blueprint" {...props}></Icon>
