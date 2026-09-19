<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j_npduomz.css';
import '../../css/p/pa7eyybxj.css';
import '../../css/i/i9odujbib.css';
import '../../css/i/i0f6qcbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="j_npduomz"/><path class="pa7eyybxj"/><path clip-rule="evenodd" class="i9odujbib"/><path class="i0f6qcbhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:bookmarks" {...props}></Icon>
