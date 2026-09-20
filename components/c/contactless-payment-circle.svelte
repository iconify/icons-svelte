<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra_a-eb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra_a-eb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:contactless-payment-circle" {...props}></Icon>
