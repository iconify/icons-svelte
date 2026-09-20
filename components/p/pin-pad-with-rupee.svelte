<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfh4p2bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lfh4p2bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pin-pad-with-rupee" {...props}></Icon>
