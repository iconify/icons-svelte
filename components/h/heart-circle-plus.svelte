<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkd7flewn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="rkd7flewn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:heart-circle-plus" {...props}></Icon>
