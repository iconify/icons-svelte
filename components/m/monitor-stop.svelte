<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uuw1qkbsv.css';
import '../../css/i/izggtwq7w.css';
import '../../css/e/e927hibau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="uuw1qkbsv"/><path class="izggtwq7w"/><path class="e927hibau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-stop" {...props}></Icon>
