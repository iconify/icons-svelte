<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvykp38uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="mvykp38uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cart-arrow-down" {...props}></Icon>
