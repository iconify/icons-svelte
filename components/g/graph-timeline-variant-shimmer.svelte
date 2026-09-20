<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb_kiboka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb_kiboka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:graph-timeline-variant-shimmer" {...props}></Icon>
