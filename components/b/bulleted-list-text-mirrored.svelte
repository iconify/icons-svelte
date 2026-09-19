<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppe2xcb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ppe2xcb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bulleted-list-text-mirrored" {...props}></Icon>
