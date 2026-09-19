<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbqzj5bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="wbqzj5bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:chevron-circle-left" {...props}></Icon>
