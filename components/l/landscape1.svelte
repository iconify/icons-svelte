<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq7ij0btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vq7ij0btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:landscape1" {...props}></Icon>
