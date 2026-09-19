<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3s0qsbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e3s0qsbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:crop-growth" {...props}></Icon>
