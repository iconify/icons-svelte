<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcss0flej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcss0flej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palette-2-line" {...props}></Icon>
