<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wotr_1b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wotr_1b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:axis-y-rotate-counterclockwise" {...props}></Icon>
