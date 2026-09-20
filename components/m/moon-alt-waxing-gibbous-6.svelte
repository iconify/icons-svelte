<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxr-zjb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="sxr-zjb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waxing-gibbous-6" {...props}></Icon>
