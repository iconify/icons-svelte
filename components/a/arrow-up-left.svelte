<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkbv50enl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zkbv50enl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrow-up-left" {...props}></Icon>
