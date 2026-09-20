<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/si-uzntbh.css';
import '../../css/y/ypigdvbdi.css';
import '../../css/x/xdt81rb6o.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="si-uzntbh"/><path class="ypigdvbdi"/><path class="xdt81rb6o"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:power-off" {...props}></Icon>
