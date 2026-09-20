<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maheqob7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maheqob7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-receipt-pause" {...props}></Icon>
