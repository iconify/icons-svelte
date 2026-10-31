<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yue8hubqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yue8hubqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bell-off-round" {...props}></Icon>
