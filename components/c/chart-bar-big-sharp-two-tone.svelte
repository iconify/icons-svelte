<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/y58fgyb3l.css';
import '../../css/p/p53xcyb3q.css';
import '../../css/r/rr87-gb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y58fgyb3l"/><path class="p53xcyb3q"/><path class="rr87-gb1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-bar-big-sharp-two-tone" {...props}></Icon>
