<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lafhkbbho.css';
import '../../css/d/dk21-1b8g.css';
import '../../css/i/i27wkwctw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lafhkbbho"/><path class="dk21-1b8g"/><path class="i27wkwctw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:circle-half-1-duo" {...props}></Icon>
