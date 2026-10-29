<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vnen35bwe.css';
import '../../css/w/w_4zjac6j.css';
import '../../css/d/dqueh1r5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vnen35bwe"/><path class="w_4zjac6j wm-shadow"/><path class="dqueh1r5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:menu-engrave" {...props}></Icon>
