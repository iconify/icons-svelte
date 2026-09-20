<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx3w-qynf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx3w-qynf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-3d-nozzle-alert" {...props}></Icon>
