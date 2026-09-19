<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myc39_jik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="myc39_jik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:device-phone-portrait" {...props}></Icon>
