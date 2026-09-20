<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujz8hjb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ujz8hjb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:international-wheelchair-symbol" {...props}></Icon>
