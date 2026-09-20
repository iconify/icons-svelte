<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs5hjpbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs5hjpbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bar-chart-grouped-fill" {...props}></Icon>
