<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl_q0b82j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sl_q0b82j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:angles-left" {...props}></Icon>
