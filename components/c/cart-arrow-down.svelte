<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6_iq1b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="c6_iq1b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cart-arrow-down" {...props}></Icon>
