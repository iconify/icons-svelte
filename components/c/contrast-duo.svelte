<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q60tyqthg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/x/xo0epvb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q60tyqthg secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="xo0epvb8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:contrast-duo" {...props}></Icon>
