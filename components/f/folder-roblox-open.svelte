<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx60lf81p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vx60lf81p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-roblox-open" {...props}></Icon>
