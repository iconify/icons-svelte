<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz6ajjbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iz6ajjbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-cog-search" {...props}></Icon>
