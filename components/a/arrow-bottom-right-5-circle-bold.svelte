<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0phu2bbs.css';
import '../../css/m/m4l-9ybuj.css';
import '../../css/d/d1yg5bchr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><circle class="m4l-9ybuj"/><path class="d1yg5bchr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-right-5-circle-bold" {...props}></Icon>
