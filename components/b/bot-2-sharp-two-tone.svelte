<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/h/h5v13_bfu.css';
import '../../css/t/tx_ah59as.css';
import '../../css/l/lvsowdyvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h5v13_bfu"/><path class="tx_ah59as"/><path class="lvsowdyvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bot-2-sharp-two-tone" {...props}></Icon>
