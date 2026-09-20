<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my7-mj9ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my7-mj9ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:draw-pen" {...props}></Icon>
