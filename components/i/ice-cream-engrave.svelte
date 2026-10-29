<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f-7gy5byl.css';
import '../../css/z/zuxl2frha.css';
import '../../css/y/ynuqnnqzn.css';
import '../../css/t/t6q0p4bxh.css';
import '../../css/e/efpyzhttl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f-7gy5byl wm-k"/><path class="wm-a zuxl2frha"/><path class="wm-shadow ynuqnnqzn"/><path class="t6q0p4bxh wm-k"/><path class="efpyzhttl wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ice-cream-engrave" {...props}></Icon>
