<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zd6c9pgot.css';
import '../../css/u/uubbag10g.css';
import '../../css/z/zzh94_b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zd6c9pgot"/><path class="uubbag10g"/><path class="zzh94_b3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pi" {...props}></Icon>
