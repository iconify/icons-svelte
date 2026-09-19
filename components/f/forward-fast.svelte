<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryy95tb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ryy95tb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:forward-fast" {...props}></Icon>
