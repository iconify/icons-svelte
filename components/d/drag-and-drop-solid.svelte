<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wee52ogfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wee52ogfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:drag-and-drop-solid" {...props}></Icon>
