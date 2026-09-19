<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2r-xbbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z2r-xbbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:red-apple" {...props}></Icon>
