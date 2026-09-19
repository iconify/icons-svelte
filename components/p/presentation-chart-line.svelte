<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ritlmmzok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ritlmmzok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:presentation-chart-line" {...props}></Icon>
