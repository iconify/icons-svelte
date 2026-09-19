<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfx04gw8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="wfx04gw8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:car-burst" {...props}></Icon>
