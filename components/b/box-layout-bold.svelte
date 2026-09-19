<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/m/m9569c2lu.css';
import '../../css/n/noetay_uo.css';
import '../../css/v/vb0af0blw.css';
import '../../css/l/lbb4fzhgj.css';
import '../../css/m/m6cnbnbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><rect class="m9569c2lu"/><path class="noetay_uo"/><rect class="vb0af0blw"/><rect class="lbb4fzhgj"/><path class="m6cnbnbyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:box-layout-bold" {...props}></Icon>
