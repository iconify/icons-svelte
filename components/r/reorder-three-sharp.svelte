<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxd4l03gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sxd4l03gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:reorder-three-sharp" {...props}></Icon>
