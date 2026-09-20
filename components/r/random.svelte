<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm6bjo4qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xm6bjo4qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:random" {...props}></Icon>
