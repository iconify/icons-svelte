<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz5z8o_px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oz5z8o_px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:perl" {...props}></Icon>
