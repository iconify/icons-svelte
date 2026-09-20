<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gakpreb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gakpreb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:gps-2" {...props}></Icon>
