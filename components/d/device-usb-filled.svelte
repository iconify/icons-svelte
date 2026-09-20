<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqs2x_bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqs2x_bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-usb-filled" {...props}></Icon>
