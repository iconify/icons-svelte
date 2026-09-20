<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r77-usbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r77-usbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-details" {...props}></Icon>
