<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dwuxk_f7w.css';
import '../../css/r/rk-8ablxs.css';
import '../../css/j/jfgbi4k4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dwuxk_f7w wm-k"/><path class="rk-8ablxs wm-k"/><path class="jfgbi4k4h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dog-sketch" {...props}></Icon>
