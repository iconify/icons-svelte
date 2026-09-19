<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fhzph8bkc.css';
import '../../css/r/r846li6xf.css';
import '../../css/l/lmk_giezu.css';
import '../../css/q/qsx_5mogf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="fhzph8bkc"/><path class="r846li6xf"/><path class="lmk_giezu"/><path class="qsx_5mogf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:map-marker-1-duo" {...props}></Icon>
