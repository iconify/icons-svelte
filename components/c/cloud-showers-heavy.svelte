<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-fonxb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j-fonxb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cloud-showers-heavy" {...props}></Icon>
