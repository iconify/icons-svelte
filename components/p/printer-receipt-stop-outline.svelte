<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3r3qrb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3r3qrb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-receipt-stop-outline" {...props}></Icon>
