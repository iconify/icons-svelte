<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v9iwk1bwv.css';
import '../../css/y/yvg5bdcoq.css';
import '../../css/o/oxa7wjbyu.css';
import '../../css/l/lte0itjcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="v9iwk1bwv"/><path class="yvg5bdcoq"/><path class="oxa7wjbyu"/><path class="lte0itjcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:binoculars-duo" {...props}></Icon>
