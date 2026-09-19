<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eb06skzns.css';
import '../../css/p/p9r-y4bkv.css';
import '../../css/j/jv0_-ib2k.css';
import '../../css/r/rxq99xbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="eb06skzns"/><path class="p9r-y4bkv"/><path class="jv0_-ib2k"/><path class="rxq99xbck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:polaroid-duo" {...props}></Icon>
