<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j037z-b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j037z-b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:lime" {...props}></Icon>
