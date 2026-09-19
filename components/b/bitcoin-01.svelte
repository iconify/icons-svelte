<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d-0kgw10j.css';
import '../../css/j/jri0z7b3j.css';
import '../../css/x/xkzi28b7v.css';
import '../../css/m/ms-vbebhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d-0kgw10j"/><path class="jri0z7b3j"/><path class="xkzi28b7v"/><path class="ms-vbebhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bitcoin-01" {...props}></Icon>
