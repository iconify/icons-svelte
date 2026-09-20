<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i1zm5vbde.css';
import '../../css/e/esnsmq0kx.css';
import '../../css/f/f97-rowio.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i1zm5vbde"/><path clip-rule="evenodd" class="esnsmq0kx"/><path clip-rule="evenodd" class="f97-rowio"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:car-off" {...props}></Icon>
