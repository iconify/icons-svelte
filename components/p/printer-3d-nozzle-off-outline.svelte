<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw4lbb9iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw4lbb9iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-3d-nozzle-off-outline" {...props}></Icon>
