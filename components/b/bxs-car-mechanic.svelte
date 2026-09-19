<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h45h-ybpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h45h-ybpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-car-mechanic" {...props}></Icon>
