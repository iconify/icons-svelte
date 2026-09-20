<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-fc-4aoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-fc-4aoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pan-horizontal" {...props}></Icon>
