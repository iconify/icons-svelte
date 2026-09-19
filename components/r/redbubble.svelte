<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztl-s4l9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztl-s4l9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:redbubble" {...props}></Icon>
