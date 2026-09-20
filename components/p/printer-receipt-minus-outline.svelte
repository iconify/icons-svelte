<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhiko34qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhiko34qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-receipt-minus-outline" {...props}></Icon>
