<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj27b0b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj27b0b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:pie-chart-2" {...props}></Icon>
