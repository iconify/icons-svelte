<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rm-idea5h.css';
import '../../css/q/qu307c6jr.css';
import '../../css/p/p21j3ibnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rm-idea5h"/><path class="qu307c6jr"/><path class="p21j3ibnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-right-through-line-duo" {...props}></Icon>
