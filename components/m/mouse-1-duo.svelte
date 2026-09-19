<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rnqb1u6-m.css';
import '../../css/w/w9l4spy6n.css';
import '../../css/e/eyibm5bwe.css';
import '../../css/u/uj50chxyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rnqb1u6-m"/><path class="w9l4spy6n"/><path class="eyibm5bwe"/><path class="uj50chxyr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mouse-1-duo" {...props}></Icon>
