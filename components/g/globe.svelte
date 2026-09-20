<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmv37bb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dmv37bb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:globe" {...props}></Icon>
