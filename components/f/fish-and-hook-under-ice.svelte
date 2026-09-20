<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9mpb1lqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l9mpb1lqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fish-and-hook-under-ice" {...props}></Icon>
