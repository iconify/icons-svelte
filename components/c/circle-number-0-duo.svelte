<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwy-oybgs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/x/xvfbro2pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwy-oybgs secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="xvfbro2pc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-number-0-duo" {...props}></Icon>
