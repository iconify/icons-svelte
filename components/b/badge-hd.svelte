<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxab2u_no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxab2u_no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:badge-hd" {...props}></Icon>
