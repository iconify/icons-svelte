<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv6bgb0wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yv6bgb0wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:loaf-of-pan-bread" {...props}></Icon>
