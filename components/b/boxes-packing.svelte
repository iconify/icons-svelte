<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0r4y3bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="a0r4y3bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:boxes-packing" {...props}></Icon>
