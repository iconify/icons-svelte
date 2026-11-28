<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rmt2jqj-j.css';
import '../../css/a/aiipvobyb.css';
import '../../css/r/r0dxi9bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rmt2jqj-j"/><path class="aiipvobyb"/><path class="r0dxi9bwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:memory-stick" {...props}></Icon>
