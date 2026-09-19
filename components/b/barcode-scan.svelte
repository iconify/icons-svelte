<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aq0r-rk9e.css';
import '../../css/i/imi_ebbbr.css';
import '../../css/r/rlrjkrbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="aq0r-rk9e"/><path class="imi_ebbbr"/><path class="rlrjkrbhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:barcode-scan" {...props}></Icon>
