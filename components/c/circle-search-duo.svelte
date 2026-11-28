<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjl2x3boh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/p/p2z-q2bky.css';
import '../../css/q/qu31vhabl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wjl2x3boh"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="p2z-q2bky"/><path class="qu31vhabl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-search-duo" {...props}></Icon>
