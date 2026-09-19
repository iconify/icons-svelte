<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0kbg_pxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="d0kbg_pxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:angle-down" {...props}></Icon>
