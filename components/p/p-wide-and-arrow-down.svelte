<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8q7uxbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z8q7uxbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:p-wide-and-arrow-down" {...props}></Icon>
