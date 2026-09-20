<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu9m68bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu9m68bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:eraser" {...props}></Icon>
