<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycbzi7r9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ycbzi7r9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:roblox-light" {...props}></Icon>
