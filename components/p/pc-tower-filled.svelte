<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thaxyb7jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="thaxyb7jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pc-tower-filled" {...props}></Icon>
