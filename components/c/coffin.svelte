<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/exb06rbxz.css';
import '../../css/u/utvepycrw.css';
import '../../css/w/wdpljiudh.css';
import '../../css/p/pg87ictwl.css';
import '../../css/a/amsnl683r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="exb06rbxz wm-k"/><path class="utvepycrw wm-deco"/><path class="wdpljiudh wm-k"/><path class="pg87ictwl wm-k"/><path class="amsnl683r wm-shadow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-valentine:coffin" {...props}></Icon>
