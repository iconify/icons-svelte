<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq3zmtb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hq3zmtb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:disk-pen" {...props}></Icon>
