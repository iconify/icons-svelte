<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hqijm0-xx.css';
import '../../css/p/p3yhwgb_q.css';
import '../../css/r/rfdm49bxm.css';
import '../../css/d/d3w2o5tno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="hqijm0-xx"/><path class="p3yhwgb_q"/><path clip-rule="evenodd" class="rfdm49bxm"/><path class="d3w2o5tno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lightbulb-1-outline" {...props}></Icon>
