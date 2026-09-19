<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy45tmhze.css';
import '../../css/g/ga0yskbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iy45tmhze"/><path class="ga0yskbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-closed-fill-16" {...props}></Icon>
