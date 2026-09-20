<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce_8b_c5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce_8b_c5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-reload-outline" {...props}></Icon>
