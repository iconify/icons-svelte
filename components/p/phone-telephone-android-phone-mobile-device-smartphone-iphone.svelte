<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0k4426mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="z0k4426mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:phone-telephone-android-phone-mobile-device-smartphone-iphone" {...props}></Icon>
