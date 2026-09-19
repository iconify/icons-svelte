<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/la-ygdc8c.css';
import '../../css/p/pah5iracu.css';
import '../../css/y/yo9a9t66o.css';
import '../../css/x/xf-_rccam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="la-ygdc8c"/><path clip-rule="evenodd" class="pah5iracu"/><path class="yo9a9t66o"/><path clip-rule="evenodd" class="xf-_rccam"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:door-outline" {...props}></Icon>
