<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v420-060z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v420-060z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-roblox" {...props}></Icon>
