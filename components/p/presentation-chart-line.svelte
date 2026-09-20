<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1enzdbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1enzdbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:presentation-chart-line" {...props}></Icon>
