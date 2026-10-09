<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1sn-9bjn.css';
import '../../css/f/fpex59k2x.css';
import '../../css/y/y0i4r3btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z1sn-9bjn"/><path class="fpex59k2x"/><path class="y0i4r3btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lpg-tank-20-bold" {...props}></Icon>
