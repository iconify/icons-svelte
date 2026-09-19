<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i06fncccs.css';
import '../../css/w/w8vwaob6g.css';
import '../../css/d/doaackbrm.css';
import '../../css/a/a8_oiabwl.css';
import '../../css/z/zy8__7bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="i06fncccs"/><path clip-rule="evenodd" class="w8vwaob6g"/><path clip-rule="evenodd" class="doaackbrm"/><path clip-rule="evenodd" class="a8_oiabwl"/><path class="zy8__7bfz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:bell-exclamation" {...props}></Icon>
