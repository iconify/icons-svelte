<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy1zqfbpa.css';
import '../../css/e/erra6gogy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy1zqfbpa"/><path class="erra6gogy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-off-bold-duotone" {...props}></Icon>
