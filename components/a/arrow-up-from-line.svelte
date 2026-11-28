<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bppo2fb_d.css';
import '../../css/d/d3em8vr4w.css';
import '../../css/t/te09yrbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bppo2fb_d"/><path class="d3em8vr4w"/><path class="te09yrbly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-from-line" {...props}></Icon>
