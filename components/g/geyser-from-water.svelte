<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvfy4cbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cvfy4cbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:geyser-from-water" {...props}></Icon>
