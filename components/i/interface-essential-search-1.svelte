<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5613cbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r5613cbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-search-1" {...props}></Icon>
