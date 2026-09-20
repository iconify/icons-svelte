<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snt7ubc3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="snt7ubc3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-battery-full-1-phone-mobile-charge-device-electricity-power-battery-full" {...props}></Icon>
