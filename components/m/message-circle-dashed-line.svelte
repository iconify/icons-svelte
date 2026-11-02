<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb3ll9hft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb3ll9hft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-dashed-line" {...props}></Icon>
