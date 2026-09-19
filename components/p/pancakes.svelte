<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aivk7ubvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aivk7ubvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:pancakes" {...props}></Icon>
