<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbcynr_zb.css';
import '../../css/m/mvifll_hv.css';
import '../../css/z/zoq1otb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nbcynr_zb"/><path class="mvifll_hv"/><path class="zoq1otb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hourglass-20" {...props}></Icon>
