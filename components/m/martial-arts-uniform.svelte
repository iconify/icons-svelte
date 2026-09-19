<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um_xhab5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="um_xhab5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:martial-arts-uniform" {...props}></Icon>
