<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/svr4a2i7c.css';
import '../../css/n/ndqjoqqah.css';
import '../../css/s/srziv7glx.css';
import '../../css/p/p4aqtdt2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="svr4a2i7c"/><path class="ndqjoqqah wm-a"/><path class="srziv7glx"/><path class="p4aqtdt2g wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:red-lantern-duo" {...props}></Icon>
