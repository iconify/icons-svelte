<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx30zxbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cx30zxbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:distribute-horizontal-left" {...props}></Icon>
