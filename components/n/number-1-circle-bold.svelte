<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0phu2bbs.css';
import '../../css/x/x7onvleiz.css';
import '../../css/m/m4l-9ybuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x7onvleiz"/><circle class="m4l-9ybuj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-1-circle-bold" {...props}></Icon>
