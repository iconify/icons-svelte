<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmag5z49h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmag5z49h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-text-send-outline" {...props}></Icon>
