<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp_1auk9l.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/a/af2wjebts.css';
import '../../css/d/dphbiab2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp_1auk9l secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="af2wjebts"/><path class="dphbiab2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-half-striped-duo" {...props}></Icon>
