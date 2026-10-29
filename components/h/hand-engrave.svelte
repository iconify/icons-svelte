<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sfh0ngpzs.css';
import '../../css/q/q-j_s-bsp.css';
import '../../css/v/vh4_jvb7b.css';
import '../../css/j/jofkexr8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sfh0ngpzs"/><path class="q-j_s-bsp wm-shadow"/><path class="vh4_jvb7b"/><path class="jofkexr8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hand-engrave" {...props}></Icon>
