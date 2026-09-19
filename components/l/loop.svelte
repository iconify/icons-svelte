<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb1v7pbfq.css';
import '../../css/m/moke7fbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pb1v7pbfq"/><path class="moke7fbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:loop" {...props}></Icon>
