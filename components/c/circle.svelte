<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydif_wb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ydif_wb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:circle" {...props}></Icon>
