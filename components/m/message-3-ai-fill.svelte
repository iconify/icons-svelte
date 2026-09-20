<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3ji-5l8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3ji-5l8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-3-ai-fill" {...props}></Icon>
