<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s14haub6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s14haub6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hexagon-line" {...props}></Icon>
