<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l05hwhz0h.css';
import '../../css/j/jygke8bny.css';
import '../../css/v/vr_4k14lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="l05hwhz0h"/><path clip-rule="evenodd" class="jygke8bny"/><path class="vr_4k14lh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:image-1" {...props}></Icon>
