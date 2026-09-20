<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w419r0bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w419r0bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:ppt" {...props}></Icon>
