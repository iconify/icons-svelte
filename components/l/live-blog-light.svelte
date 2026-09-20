<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjw4l9poi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jjw4l9poi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:live-blog-light" {...props}></Icon>
