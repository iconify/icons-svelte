<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r7n36fb4k.css';
import '../../css/z/zub4acc2g.css';
import '../../css/v/vwzncsbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="r7n36fb4k"/><path class="wm-a zub4acc2g"/><path class="vwzncsbmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-right-close-duo" {...props}></Icon>
