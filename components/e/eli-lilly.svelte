<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idwguvbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":631,"height":344};
const content = `<path class="idwguvbwi layer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eli-lilly" {...props}></Icon>
