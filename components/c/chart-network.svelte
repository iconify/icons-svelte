<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hc1yluhcl.css';
import '../../css/n/na3-2yfwb.css';
import '../../css/n/nwehtcbqh.css';
import '../../css/n/nh-ps30pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hc1yluhcl"/><path class="na3-2yfwb"/><path class="nwehtcbqh"/><path class="nh-ps30pw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-network" {...props}></Icon>
