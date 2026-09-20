<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t00jw3bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t00jw3bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:brackets-angle" {...props}></Icon>
