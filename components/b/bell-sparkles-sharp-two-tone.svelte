<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/f769viv2h.css';
import '../../css/c/c6upwkbge.css';
import '../../css/o/ootzhpboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f769viv2h"/><path class="c6upwkbge"/><path class="ootzhpboc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell-sparkles-sharp-two-tone" {...props}></Icon>
