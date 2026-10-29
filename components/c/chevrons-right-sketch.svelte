<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dt464gbll.css';
import '../../css/l/lprg8mgvy.css';
import '../../css/d/dvwvpibet.css';
import '../../css/u/u4ulct2az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dt464gbll wm-k"/><path class="lprg8mgvy wm-a"/><path class="dvwvpibet wm-k"/><path class="u4ulct2az wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevrons-right-sketch" {...props}></Icon>
