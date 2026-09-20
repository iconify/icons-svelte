<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhj1m7b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mhj1m7b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cart-arrow-down" {...props}></Icon>
