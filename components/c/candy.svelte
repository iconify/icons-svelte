<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3v0e9b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x3v0e9b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:candy" {...props}></Icon>
