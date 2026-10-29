<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vw2d3v36t.css';
import '../../css/g/gjffvyjta.css';
import '../../css/z/z2cmsqfjo.css';
import '../../css/m/m8z7zkbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vw2d3v36t"/><path class="gjffvyjta wm-a"/><path class="z2cmsqfjo"/><path class="m8z7zkbik wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:minimize-duo" {...props}></Icon>
