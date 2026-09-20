<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnfx4bcxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1537};
const content = `<path class="rnfx4bcxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-waxing-crescent-6" {...props}></Icon>
