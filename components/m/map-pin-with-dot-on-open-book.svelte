<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz8ow6yfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fz8ow6yfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:map-pin-with-dot-on-open-book" {...props}></Icon>
