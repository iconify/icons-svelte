<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/l/lzz8rsb8x.css';
import '../../css/r/rn3jg9bjb.css';
import '../../css/g/g5z6ynbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ud95brdct"/><path class="lzz8rsb8x"/><path class="rn3jg9bjb"/><path class="g5z6ynbzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-pi" {...props}></Icon>
