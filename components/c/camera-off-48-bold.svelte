<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxo5tubhm.css';
import '../../css/c/cw-sa1-6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mxo5tubhm"/><path class="cw-sa1-6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-off-48-bold" {...props}></Icon>
