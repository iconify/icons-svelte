<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j62xyjbvv.css';
import '../../css/u/u4mr4cc1c.css';
import '../../css/y/yw4actbtc.css';
import '../../css/e/evlq5sb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j62xyjbvv wm-k"/><path class="u4mr4cc1c wm-a"/><path class="wm-k yw4actbtc"/><path class="evlq5sb4r wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:person-swimming-sketch" {...props}></Icon>
