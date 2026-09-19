<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csvco9ssf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="csvco9ssf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:leg" {...props}></Icon>
