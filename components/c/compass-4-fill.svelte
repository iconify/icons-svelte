<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usb24irbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usb24irbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:compass-4-fill" {...props}></Icon>
