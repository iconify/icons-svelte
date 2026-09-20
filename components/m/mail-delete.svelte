<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqxl6yy8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqxl6yy8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mail-delete" {...props}></Icon>
