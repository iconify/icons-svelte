<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rg96irb-q.css';
import '../../css/b/bm3ps4bdp.css';
import '../../css/a/a2kumftht.css';
import '../../css/o/owgj5rxcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rg96irb-q"/><path clip-rule="evenodd" class="bm3ps4bdp"/><path class="a2kumftht"/><path clip-rule="evenodd" class="owgj5rxcv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-50-outline" {...props}></Icon>
