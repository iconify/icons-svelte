<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/ptl0otbdr.css';
import '../../css/d/d2e0hniif.css';
import '../../css/o/on4mi1mmc.css';
import '../../css/s/smvgl5sak.css';
import '../../css/l/lr-9pmbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ptl0otbdr"/><path clip-rule="evenodd" class="d2e0hniif"/><path class="on4mi1mmc"/><path class="smvgl5sak"/><path class="lr-9pmbpr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:grin-tears" {...props}></Icon>
