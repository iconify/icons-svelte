<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1x3--bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y1x3--bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:earth-americas-filled" {...props}></Icon>
