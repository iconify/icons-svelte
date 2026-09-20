<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn3_w6buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xn3_w6buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:hanging-rail" {...props}></Icon>
