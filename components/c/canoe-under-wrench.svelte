<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls58l8zhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ls58l8zhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canoe-under-wrench" {...props}></Icon>
