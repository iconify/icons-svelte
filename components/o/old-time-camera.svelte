<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jadl1ismj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jadl1ismj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:old-time-camera" {...props}></Icon>
