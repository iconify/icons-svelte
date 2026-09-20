<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izc259z0t.css';
import '../../css/u/u29y0z2tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="izc259z0t"/><path class="u29y0z2tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-copy" {...props}></Icon>
