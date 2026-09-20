<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx3ux99nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yx3ux99nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mounted-slotted-dispenser" {...props}></Icon>
