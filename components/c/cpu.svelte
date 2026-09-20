<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-xii8b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-xii8b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cpu" {...props}></Icon>
