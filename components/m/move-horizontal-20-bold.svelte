<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne19vg9-n.css';
import '../../css/n/n0aw6mhri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ne19vg9-n"/><path class="n0aw6mhri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:move-horizontal-20-bold" {...props}></Icon>
