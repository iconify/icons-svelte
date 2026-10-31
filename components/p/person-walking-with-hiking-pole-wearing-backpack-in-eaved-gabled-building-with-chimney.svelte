<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/req6_nvhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="req6_nvhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-with-hiking-pole-wearing-backpack-in-eaved-gabled-building-with-chimney" {...props}></Icon>
