<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp589yb-g.css';
import '../../css/e/esg1j5bfl.css';
import '../../css/i/ixcfylb1s.css';
import '../../css/d/d8tx-pb_g.css';
import '../../css/q/qndg8fbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vp589yb-g"/><path class="esg1j5bfl"/><path class="ixcfylb1s"/><path class="d8tx-pb_g"/><path class="qndg8fbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:robot-arm-48" {...props}></Icon>
