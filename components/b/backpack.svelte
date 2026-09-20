<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5r7-4nmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5r7-4nmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:backpack" {...props}></Icon>
