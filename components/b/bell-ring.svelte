<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwrnt-b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwrnt-b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:bell-ring" {...props}></Icon>
