<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6h62zf0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6h62zf0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-receipt-play" {...props}></Icon>
