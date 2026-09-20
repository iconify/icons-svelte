<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/b/bvb7sibpb.css';
import '../../css/i/i5qce4b9c.css';
import '../../css/m/m08nw2b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bvb7sibpb"/><path class="i5qce4b9c"/><path class="m08nw2b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:archive-sharp-duotone" {...props}></Icon>
