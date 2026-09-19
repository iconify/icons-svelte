<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv6d6372h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kv6d6372h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:node-js" {...props}></Icon>
