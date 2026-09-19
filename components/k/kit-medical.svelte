<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh0i0ccvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="dh0i0ccvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:kit-medical" {...props}></Icon>
