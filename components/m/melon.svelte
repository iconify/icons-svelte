<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5knh5b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e5knh5b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:melon" {...props}></Icon>
