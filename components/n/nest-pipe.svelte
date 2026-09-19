<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxveh1bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vxveh1bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nest-pipe" {...props}></Icon>
