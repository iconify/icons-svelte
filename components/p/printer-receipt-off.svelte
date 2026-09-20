<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiz7z0ihj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tiz7z0ihj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-receipt-off" {...props}></Icon>
