<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sj279cslk.css';
import '../../css/k/k4othtbmn.css';
import '../../css/t/t99xelbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="sj279cslk"/><path class="k4othtbmn wm-a"/><path class="t99xelbnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mail-open-duo" {...props}></Icon>
