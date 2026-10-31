<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yewjnwgxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yewjnwgxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:code-sparkle-round" {...props}></Icon>
