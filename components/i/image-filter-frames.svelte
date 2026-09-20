<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0_cx4rfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0_cx4rfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-filter-frames" {...props}></Icon>
