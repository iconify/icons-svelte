<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uuw1qkbsv.css';
import '../../css/i/izggtwq7w.css';
import '../../css/s/sxr14vmgm.css';
import '../../css/n/n6d6eun0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="uuw1qkbsv"/><path class="izggtwq7w"/><path class="sxr14vmgm"/><path class="n6d6eun0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-user" {...props}></Icon>
