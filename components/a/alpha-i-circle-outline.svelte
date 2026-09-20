<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt6788bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt6788bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-i-circle-outline" {...props}></Icon>
