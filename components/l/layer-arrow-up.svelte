<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r0d20pbmo.css';
import '../../css/o/owoni5tju.css';
import '../../css/w/w8dto046u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="r0d20pbmo"/><path class="owoni5tju"/><path class="w8dto046u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layer-arrow-up" {...props}></Icon>
