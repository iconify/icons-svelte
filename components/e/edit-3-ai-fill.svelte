<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnhd3fn8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnhd3fn8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-3-ai-fill" {...props}></Icon>
