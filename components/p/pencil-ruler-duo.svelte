<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nuu7pj2tk.css';
import '../../css/a/agr8unbte.css';
import '../../css/l/la1njcbhy.css';
import '../../css/w/wawkbcc0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nuu7pj2tk"/><path class="agr8unbte wm-a"/><path class="la1njcbhy"/><path class="wawkbcc0p wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pencil-ruler-duo" {...props}></Icon>
