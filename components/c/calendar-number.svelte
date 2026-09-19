<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn_uo6biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vn_uo6biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:calendar-number" {...props}></Icon>
