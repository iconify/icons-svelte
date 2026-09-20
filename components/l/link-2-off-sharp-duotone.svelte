<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/a8f231k-x.css';
import '../../css/a/ahhqo1b4s.css';
import '../../css/e/ellalvbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a8f231k-x"/><path class="ahhqo1b4s"/><path class="ellalvbgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:link-2-off-sharp-duotone" {...props}></Icon>
