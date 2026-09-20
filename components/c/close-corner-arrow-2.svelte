<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssip8gfhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ssip8gfhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:close-corner-arrow-2" {...props}></Icon>
