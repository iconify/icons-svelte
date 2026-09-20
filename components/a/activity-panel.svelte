<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c71yqfbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c71yqfbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:activity-panel" {...props}></Icon>
