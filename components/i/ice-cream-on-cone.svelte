<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq2zj9bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vq2zj9bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ice-cream-on-cone" {...props}></Icon>
