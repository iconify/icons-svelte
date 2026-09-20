<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lafomvmft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lafomvmft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:hotel-14" {...props}></Icon>
