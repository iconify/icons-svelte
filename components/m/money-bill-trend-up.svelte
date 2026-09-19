<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vny3_-bya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vny3_-bya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:money-bill-trend-up" {...props}></Icon>
