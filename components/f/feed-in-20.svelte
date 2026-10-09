<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wub9asb0k.css';
import '../../css/s/sgi1483fh.css';
import '../../css/v/vxtaxskvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wub9asb0k"/><path class="sgi1483fh"/><path class="vxtaxskvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:feed-in-20" {...props}></Icon>
