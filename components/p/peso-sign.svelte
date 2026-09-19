<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fff_zr3dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="fff_zr3dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:peso-sign" {...props}></Icon>
