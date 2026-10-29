<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pywsmcckd.css';
import '../../css/v/vvr311bdw.css';
import '../../css/m/mhhe0cccx.css';
import '../../css/a/avlazkjhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pywsmcckd wm-k"/><path class="vvr311bdw wm-a"/><path class="mhhe0cccx wm-k"/><path class="avlazkjhj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-left-to-line-sketch" {...props}></Icon>
