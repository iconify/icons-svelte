<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk_d2pbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yk_d2pbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-with-hiking-pole-wearing-backpack-in-eaved-gabled-building" {...props}></Icon>
