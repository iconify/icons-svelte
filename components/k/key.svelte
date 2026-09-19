<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc2i8buif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tc2i8buif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:key" {...props}></Icon>
