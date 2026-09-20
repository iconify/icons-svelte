<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfsepcp4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mfsepcp4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:eraser" {...props}></Icon>
