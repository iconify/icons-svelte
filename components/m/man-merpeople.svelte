<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfa4yvn9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zfa4yvn9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:man-merpeople" {...props}></Icon>
