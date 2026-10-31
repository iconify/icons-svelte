<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaxcpue-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaxcpue-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:move-horizontal-bulk-round" {...props}></Icon>
