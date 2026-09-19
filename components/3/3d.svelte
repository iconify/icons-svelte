<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0g1y97nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f0g1y97nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:3d" {...props}></Icon>
