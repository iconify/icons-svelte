<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydgeh8l8d.css';
import '../../css/y/yp7spr8cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ydgeh8l8d"/><path class="yp7spr8cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cake-20" {...props}></Icon>
