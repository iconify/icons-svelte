<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pqbe3sw2q.css';
import '../../css/l/litn8rban.css';
import '../../css/z/z5ue-mb9z.css';
import '../../css/u/uxaf0_brb.css';
import '../../css/y/yu9sii_3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pqbe3sw2q"/><path class="litn8rban wm-shadow"/><path class="z5ue-mb9z"/><path class="uxaf0_brb"/><path class="yu9sii_3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:christmas-candle-engrave" {...props}></Icon>
