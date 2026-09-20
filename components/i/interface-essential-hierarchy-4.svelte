<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liim8eenz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="liim8eenz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-hierarchy-4" {...props}></Icon>
