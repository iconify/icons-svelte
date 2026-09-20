<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeibzhb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeibzhb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:donut-chart-fill" {...props}></Icon>
