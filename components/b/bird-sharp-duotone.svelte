<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/k9nr61bta.css';
import '../../css/k/kfsr_4elq.css';
import '../../css/j/jbg64mbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k9nr61bta"/><path class="kfsr_4elq"/><path class="jbg64mbay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bird-sharp-duotone" {...props}></Icon>
