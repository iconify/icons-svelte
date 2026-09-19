<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtsp6793c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rtsp6793c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:blz" {...props}></Icon>
