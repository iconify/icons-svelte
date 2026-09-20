<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/p/pc44scclm.css';
import '../../css/r/rau-pebxg.css';
import '../../css/j/jkh-81bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pc44scclm"/><path class="rau-pebxg"/><path class="jkh-81bok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:earbuds-sharp-two-tone" {...props}></Icon>
