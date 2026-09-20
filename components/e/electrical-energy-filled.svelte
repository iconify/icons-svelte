<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgm1b6z5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pgm1b6z5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:electrical-energy-filled" {...props}></Icon>
