<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/e/enjc3_bdq.css';
import '../../css/m/mjt0l_brl.css';
import '../../css/f/fq5xfrb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="enjc3_bdq"/><path class="mjt0l_brl"/><path class="fq5xfrb-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card-sparkles-sharp-two-tone" {...props}></Icon>
