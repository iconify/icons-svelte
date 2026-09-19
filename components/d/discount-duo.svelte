<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r8yxl582h.css';
import '../../css/r/rvcv5yw0j.css';
import '../../css/t/tzdbdn7ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="r8yxl582h"/><path class="rvcv5yw0j"/><path class="tzdbdn7ho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:discount-duo" {...props}></Icon>
