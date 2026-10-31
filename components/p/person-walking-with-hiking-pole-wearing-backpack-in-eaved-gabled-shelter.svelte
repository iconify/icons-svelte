<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw7imihcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pw7imihcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-with-hiking-pole-wearing-backpack-in-eaved-gabled-shelter" {...props}></Icon>
