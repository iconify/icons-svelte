<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veyiifbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veyiifbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-chart-check-outline" {...props}></Icon>
