<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv5vt-b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fv5vt-b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:geyser-from-ground" {...props}></Icon>
