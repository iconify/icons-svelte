<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd_z6iuxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd_z6iuxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:drag-and-drop" {...props}></Icon>
