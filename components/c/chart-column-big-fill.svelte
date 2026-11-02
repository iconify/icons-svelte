<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-_a2ccer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-_a2ccer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-column-big-fill" {...props}></Icon>
