<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bub6scbyt.css';
import '../../css/c/c7zikwrvh.css';
import '../../css/f/f08krvjen.css';
import '../../css/x/xc_fo9bdv.css';
import '../../css/f/f26ggybga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bub6scbyt"/><path class="c7zikwrvh"/><path class="f08krvjen"/><path class="xc_fo9bdv"/><path class="f26ggybga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fridge-linear" {...props}></Icon>
