<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h7kc_s51c.css';
import '../../css/r/rgcaz9bqd.css';
import '../../css/h/hw-s9nbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="h7kc_s51c"/><path class="rgcaz9bqd"/><path class="hw-s9nbyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:bed" {...props}></Icon>
