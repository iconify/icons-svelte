<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zes8_9b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zes8_9b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:first-aid" {...props}></Icon>
