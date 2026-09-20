<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7_dlbcgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="w7_dlbcgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-alt-rain-wind" {...props}></Icon>
