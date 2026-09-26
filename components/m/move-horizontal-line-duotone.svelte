<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/ti-w8z23v.css';
import '../../css/i/ist54rbfb.css';
import '../../css/p/p1oh4ubnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ti-w8z23v"/><path class="ist54rbfb"/><path class="p1oh4ubnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-horizontal-line-duotone" {...props}></Icon>
