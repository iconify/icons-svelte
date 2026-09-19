<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx0y8b1vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cx0y8b1vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rexx" {...props}></Icon>
