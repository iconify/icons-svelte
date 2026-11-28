<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ammxg4bjk.css';
import '../../css/u/u_b68ubpu.css';
import '../../css/s/sbwgwr0cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ammxg4bjk"/><path class="u_b68ubpu"/><path class="sbwgwr0cg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ratio" {...props}></Icon>
