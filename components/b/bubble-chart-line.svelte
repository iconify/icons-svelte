<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdxbmxx-r.css';
import '../../css/f/fvlx95mhf.css';
import '../../css/f/fwqnodhwv.css';
import '../../css/q/qz9_vybvb.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 tdxbmxx-r"/><path class="clr-i-outline clr-i-outline-path-2 fvlx95mhf"/><path class="clr-i-outline clr-i-outline-path-3 fwqnodhwv"/><path class="clr-i-outline clr-i-outline-path-4 qz9_vybvb"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:bubble-chart-line" {...props}></Icon>
