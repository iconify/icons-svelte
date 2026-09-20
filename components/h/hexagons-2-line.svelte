<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr2zztb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr2zztb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hexagons-2-line" {...props}></Icon>
