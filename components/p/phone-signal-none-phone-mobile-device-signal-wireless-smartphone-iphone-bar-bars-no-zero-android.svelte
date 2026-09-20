<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzk5aq42g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pzk5aq42g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:phone-signal-none-phone-mobile-device-signal-wireless-smartphone-iphone-bar-bars-no-zero-android" {...props}></Icon>
