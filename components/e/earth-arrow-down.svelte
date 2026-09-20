<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrby--51b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrby--51b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:earth-arrow-down" {...props}></Icon>
