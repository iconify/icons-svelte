<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/c/c6k5pz9qf.css';
import '../../css/a/aa1oedcpg.css';
import '../../css/f/fly5esi0x.css';
import '../../css/x/xfyuoc22x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="c6k5pz9qf wm-deco"/><path class="aa1oedcpg wm-deco"/><path class="fly5esi0x wm-k"/><path class="wm-a xfyuoc22x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:battery-medium-blueprint" {...props}></Icon>
