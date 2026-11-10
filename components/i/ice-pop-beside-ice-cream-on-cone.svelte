<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hglofqdlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hglofqdlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ice-pop-beside-ice-cream-on-cone" {...props}></Icon>
