<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/p/p34tvj1eg.css';
import '../../css/c/c6upwkbge.css';
import '../../css/u/u5618s-wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p34tvj1eg"/><path class="c6upwkbge"/><path class="u5618s-wt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-sparkles-sharp-two-tone" {...props}></Icon>
