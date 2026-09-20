<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/u/u09znn34h.css';
import '../../css/p/pv4cg3-5q.css';
import '../../css/r/ra-o12qfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="u09znn34h"/><path class="pv4cg3-5q"/><path class="ra-o12qfd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:add-collection" {...props}></Icon>
