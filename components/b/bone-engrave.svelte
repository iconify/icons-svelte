<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p1vtcqu8x.css';
import '../../css/v/v8yvcacmt.css';
import '../../css/y/yrnv22bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p1vtcqu8x"/><path class="v8yvcacmt wm-shadow"/><path class="yrnv22bjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bone-engrave" {...props}></Icon>
