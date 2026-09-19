<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jkte7ebxp.css';
import '../../css/r/rt809ylhh.css';
import '../../css/x/x2dwaybup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="jkte7ebxp"/><path class="rt809ylhh"/><path class="x2dwaybup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:map-marker-line-duo" {...props}></Icon>
