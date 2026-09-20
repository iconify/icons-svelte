<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7gb1fb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i7gb1fb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:binoculars" {...props}></Icon>
