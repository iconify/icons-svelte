<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlmp_l8be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlmp_l8be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-check-round" {...props}></Icon>
