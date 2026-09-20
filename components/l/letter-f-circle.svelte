<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-h9fkyoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-h9fkyoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-f-circle" {...props}></Icon>
