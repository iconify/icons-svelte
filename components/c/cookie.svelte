<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evhdcpftq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="evhdcpftq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cookie" {...props}></Icon>
