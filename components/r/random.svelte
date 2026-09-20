<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8x7bwbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h8x7bwbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:random" {...props}></Icon>
