<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w92xktbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w92xktbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:banana" {...props}></Icon>
