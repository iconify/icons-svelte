<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca3p3fdcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ca3p3fdcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-ss" {...props}></Icon>
