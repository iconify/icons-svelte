<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/ndvufqr1x.css';
import '../../css/l/l-t4b1bzb.css';
import '../../css/b/b5x9xi0bu.css';
import '../../css/c/c5b0y0tyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ndvufqr1x"/><path class="l-t4b1bzb wm-a"/><path class="b5x9xi0bu wm-a"/><path class="c5b0y0tyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:copy-duo" {...props}></Icon>
