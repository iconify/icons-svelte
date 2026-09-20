<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn9z0ybli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn9z0ybli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-receipt-pause-outline" {...props}></Icon>
