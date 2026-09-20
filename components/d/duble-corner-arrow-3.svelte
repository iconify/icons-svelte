<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahy-3rbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ahy-3rbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:duble-corner-arrow-3" {...props}></Icon>
