<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z5s_iw4ay.css';
import '../../css/d/dr0xlqb2l.css';
import '../../css/r/r7nyb4b5e.css';
import '../../css/t/t0rxzi1ao.css';
import '../../css/g/gp4e8i8_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="z5s_iw4ay"/><path class="dr0xlqb2l"/><path class="r7nyb4b5e"/><path class="t0rxzi1ao"/><path class="gp4e8i8_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:baseball" {...props}></Icon>
