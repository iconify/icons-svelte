<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/f5fyfeb4d.css';
import '../../css/m/mj045rbhx.css';
import '../../css/e/esq8rfb3o.css';
import '../../css/d/d46rvgxqo.css';
import '../../css/y/y7g4hb6ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="f5fyfeb4d wm-deco"/><path class="mj045rbhx wm-deco"/><path class="esq8rfb3o wm-deco"/><path class="d46rvgxqo wm-k"/><path class="wm-a y7g4hb6ig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hand-coins-blueprint" {...props}></Icon>
