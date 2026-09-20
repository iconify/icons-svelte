<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/n/n2lht5b1f.css';
import '../../css/j/jyrpkpb6l.css';
import '../../css/r/rj2y4vkzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n2lht5b1f"/><path class="jyrpkpb6l"/><path class="rj2y4vkzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:airpods-open-sharp-duotone" {...props}></Icon>
