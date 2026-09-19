<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tbdb0_b1z.css';
import '../../css/b/byun9ebyr.css';
import '../../css/v/vt-vg_b-u.css';
import '../../css/b/bjs1nx4cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="tbdb0_b1z"/><path clip-rule="evenodd" class="byun9ebyr"/><path clip-rule="evenodd" class="vt-vg_b-u"/><path class="bjs1nx4cv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:queen" {...props}></Icon>
