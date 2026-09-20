<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eobp_3bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eobp_3bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-y" {...props}></Icon>
