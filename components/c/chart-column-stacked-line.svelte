<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sijc31_mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sijc31_mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-column-stacked-line" {...props}></Icon>
