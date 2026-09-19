<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6j691ats.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x6j691ats"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:clapper-board" {...props}></Icon>
