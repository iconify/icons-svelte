<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xs1p5p0xc.css';
import '../../css/a/adjqzl9mh.css';
import '../../css/u/uf50r_q1t.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xs1p5p0xc"/><path clip-rule="evenodd" class="adjqzl9mh"/><path class="uf50r_q1t"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:face-smiling-off" {...props}></Icon>
