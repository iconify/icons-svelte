<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh1vxe8iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uh1vxe8iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:minecart" {...props}></Icon>
