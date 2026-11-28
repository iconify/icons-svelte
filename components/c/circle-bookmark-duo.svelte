<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe5-t3bgs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/h/hm3mo31xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe5-t3bgs secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="hm3mo31xb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-bookmark-duo" {...props}></Icon>
