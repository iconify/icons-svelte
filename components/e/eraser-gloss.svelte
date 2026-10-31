<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmk-q3y2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmk-q3y2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:eraser-gloss" {...props}></Icon>
