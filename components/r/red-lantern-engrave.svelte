<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sog12ps8i.css';
import '../../css/p/p4ir0zbci.css';
import '../../css/z/zo9l4m5qv.css';
import '../../css/s/srziv7glx.css';
import '../../css/c/cojk3quut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sog12ps8i wm-k"/><path class="p4ir0zbci wm-a"/><path class="wm-shadow zo9l4m5qv"/><path class="srziv7glx wm-k"/><path class="cojk3quut wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:red-lantern-engrave" {...props}></Icon>
