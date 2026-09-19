<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t059a5r9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t059a5r9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:airplane" {...props}></Icon>
