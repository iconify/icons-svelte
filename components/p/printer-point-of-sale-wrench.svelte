<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct8u88f6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct8u88f6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-point-of-sale-wrench" {...props}></Icon>
