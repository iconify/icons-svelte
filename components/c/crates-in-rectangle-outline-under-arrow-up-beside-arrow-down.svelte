<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj1tirh6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pj1tirh6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:crates-in-rectangle-outline-under-arrow-up-beside-arrow-down" {...props}></Icon>
