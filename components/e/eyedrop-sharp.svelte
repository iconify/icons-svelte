<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv9bggb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zv9bggb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:eyedrop-sharp" {...props}></Icon>
