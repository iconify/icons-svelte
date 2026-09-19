<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7usbhbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="l7usbhbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:acclaim-square" {...props}></Icon>
