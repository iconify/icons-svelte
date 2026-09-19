<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph_x37bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ph_x37bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:recycle" {...props}></Icon>
