<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yjy9_xhih.css';
import '../../css/d/dtjbxibrj.css';
import '../../css/v/vzi1xbcty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yjy9_xhih"/><path class="dtjbxibrj"/><path class="vzi1xbcty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-lock-check-01" {...props}></Icon>
