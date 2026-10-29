<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bd2t1bccx.css';
import '../../css/f/fqpodu9zv.css';
import '../../css/u/ugnb4kbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bd2t1bccx"/><path class="fqpodu9zv wm-a"/><path class="ugnb4kbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:paint-roller" {...props}></Icon>
