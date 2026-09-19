<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i9dlazb0p.css';
import '../../css/l/lu5-4oist.css';
import '../../css/r/reyjvibzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="i9dlazb0p"/><path class="lu5-4oist"/><path class="reyjvibzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:briefcase-medical-duo" {...props}></Icon>
