<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miy_awb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":616,"height":512};
const content = `<path class="miy_awb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:cloudversify" {...props}></Icon>
