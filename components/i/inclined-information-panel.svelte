<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbg7o3_pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dbg7o3_pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:inclined-information-panel" {...props}></Icon>
