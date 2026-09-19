<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d05jkvbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d05jkvbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:green-book" {...props}></Icon>
