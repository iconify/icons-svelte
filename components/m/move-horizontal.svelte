<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b4eqebb1f.css';
import '../../css/o/omhuwgbnv.css';
import '../../css/t/tk3xwsbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b4eqebb1f"/><path class="omhuwgbnv"/><path class="tk3xwsbbh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:move-horizontal" {...props}></Icon>
