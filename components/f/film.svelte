<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z78iq229s.css';
import '../../css/e/e37y0sbcn.css';
import '../../css/m/mig00zq1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="z78iq229s"/><path clip-rule="evenodd" class="e37y0sbcn"/><path class="mig00zq1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:film" {...props}></Icon>
