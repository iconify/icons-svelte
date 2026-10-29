<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bhy4-61wh.css';
import '../../css/i/iwu-0yrln.css';
import '../../css/k/kyiupabxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bhy4-61wh"/><path class="iwu-0yrln wm-a"/><path class="kyiupabxi wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flip-horizontal" {...props}></Icon>
