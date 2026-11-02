<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se9_lvtty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se9_lvtty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flashlight-off-line" {...props}></Icon>
