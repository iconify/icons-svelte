<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syfev4bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="syfev4bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bookmark-filled" {...props}></Icon>
