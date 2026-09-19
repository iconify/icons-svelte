<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r11mf4_ss.css';
import '../../css/y/ydudqy-kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r11mf4_ss"/><path class="ydudqy-kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:magnet-sharp" {...props}></Icon>
