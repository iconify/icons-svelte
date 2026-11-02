<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqcf3038h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqcf3038h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-bar-stacked-fill" {...props}></Icon>
