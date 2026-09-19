<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2112k_vg.css';
import '../../css/y/y2nmqhmom.css';
import '../../css/g/gdrmk4bfv.css';
import '../../css/s/smfv_omyd.css';
import '../../css/y/yrwibac8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r2112k_vg"/><path class="y2nmqhmom"/><path class="gdrmk4bfv"/><path class="smfv_omyd"/><path class="yrwibac8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:huoshanzhibo" {...props}></Icon>
