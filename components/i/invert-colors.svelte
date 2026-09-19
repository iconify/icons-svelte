<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9owf8b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":416};
const content = `<path class="l9owf8b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:invert-colors" {...props}></Icon>
