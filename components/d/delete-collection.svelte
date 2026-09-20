<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/v/vsv0pig3s.css';
import '../../css/r/ra-o12qfd.css';
import '../../css/p/pv4cg3-5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="vsv0pig3s"/><path class="ra-o12qfd"/><path class="pv4cg3-5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:delete-collection" {...props}></Icon>
