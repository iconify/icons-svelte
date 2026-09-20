<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzpjhuv5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uzpjhuv5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:draw-ellipse-segment" {...props}></Icon>
