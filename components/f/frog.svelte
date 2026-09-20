<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t70mwlbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t70mwlbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:frog" {...props}></Icon>
