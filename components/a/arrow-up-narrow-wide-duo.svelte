<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e-6_wy83u.css';
import '../../css/m/myfgyn8nz.css';
import '../../css/c/ceohyg-cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="e-6_wy83u"/><path class="myfgyn8nz"/><path class="ceohyg-cf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-narrow-wide-duo" {...props}></Icon>
