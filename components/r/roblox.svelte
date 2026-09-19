<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i56jn-xon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i56jn-xon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:roblox" {...props}></Icon>
