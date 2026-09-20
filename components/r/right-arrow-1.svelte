<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz3uhdcoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tz3uhdcoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:right-arrow-1" {...props}></Icon>
