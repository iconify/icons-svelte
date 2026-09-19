<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxccxrp4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mxccxrp4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-xmark" {...props}></Icon>
