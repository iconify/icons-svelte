<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahi4ik3zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahi4ik3zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:borobudur" {...props}></Icon>
