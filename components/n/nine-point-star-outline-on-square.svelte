<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbe_w6b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kbe_w6b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:nine-point-star-outline-on-square" {...props}></Icon>
