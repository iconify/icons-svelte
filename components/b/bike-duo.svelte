<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oy4egu67j.css';
import '../../css/e/ed6fslw1h.css';
import '../../css/w/w7ft8mb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="oy4egu67j"/><path class="ed6fslw1h"/><path class="w7ft8mb7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bike-duo" {...props}></Icon>
