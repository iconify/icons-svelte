<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcaqm5mvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcaqm5mvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:card-id" {...props}></Icon>
