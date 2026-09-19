<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9o73ac4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r9o73ac4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:airport-location" {...props}></Icon>
