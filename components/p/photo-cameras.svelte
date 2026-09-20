<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvy1pfbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tvy1pfbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:photo-cameras" {...props}></Icon>
