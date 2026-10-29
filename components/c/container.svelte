<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gc_-hub4z.css';
import '../../css/t/tsqe1pboz.css';
import '../../css/l/lq23_x48i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gc_-hub4z"/><path class="tsqe1pboz"/><path class="lq23_x48i wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:container" {...props}></Icon>
