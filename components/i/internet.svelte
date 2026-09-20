<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kg8qh2bhc.css';
import '../../css/g/g_m248b8z.css';
import '../../css/t/tely9lb-g.css';
import '../../css/y/y4yl88bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="kg8qh2bhc"/><path clip-rule="evenodd" class="g_m248b8z"/><path clip-rule="evenodd" class="tely9lb-g"/><path class="y4yl88bpn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:internet" {...props}></Icon>
