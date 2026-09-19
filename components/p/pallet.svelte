<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2d2h3csf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="h2d2h3csf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:pallet" {...props}></Icon>
