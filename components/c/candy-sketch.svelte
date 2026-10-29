<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wfo5e4vzc.css';
import '../../css/t/tnmupxbzr.css';
import '../../css/t/td21-u-yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wfo5e4vzc"/><path class="tnmupxbzr"/><path class="td21-u-yi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:candy-sketch" {...props}></Icon>
