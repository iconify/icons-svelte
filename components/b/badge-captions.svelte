<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rowf91b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rowf91b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:badge-captions" {...props}></Icon>
