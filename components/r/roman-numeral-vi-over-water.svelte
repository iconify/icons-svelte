<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p05ebdbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p05ebdbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-vi-over-water" {...props}></Icon>
