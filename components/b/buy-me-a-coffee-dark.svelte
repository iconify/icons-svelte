<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i68-4kbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i68-4kbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:buy-me-a-coffee-dark" {...props}></Icon>
