<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl4-1xb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl4-1xb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-chart-check" {...props}></Icon>
