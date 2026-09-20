<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbn03r-oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zbn03r-oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-battery-low-1-phone-mobile-charge-device-electricity-power-battery-low" {...props}></Icon>
