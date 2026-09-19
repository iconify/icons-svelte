<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6eihob5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z6eihob5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:closed-caption-filled" {...props}></Icon>
