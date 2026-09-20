<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2jlrngzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2jlrngzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:network-device" {...props}></Icon>
