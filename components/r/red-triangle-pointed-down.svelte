<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy4pajm8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wy4pajm8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:red-triangle-pointed-down" {...props}></Icon>
