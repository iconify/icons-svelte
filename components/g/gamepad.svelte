<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf700_lzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="vf700_lzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:gamepad" {...props}></Icon>
