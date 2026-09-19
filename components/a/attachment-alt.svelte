<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmi81oi2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":480};
const content = `<path class="jmi81oi2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:attachment-alt" {...props}></Icon>
