<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lg4hmt8ek.css';
import '../../css/v/vgjwohkdf.css';
import '../../css/z/z7txwwbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lg4hmt8ek"/><path class="vgjwohkdf"/><path class="z7txwwbpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-line-duotone" {...props}></Icon>
