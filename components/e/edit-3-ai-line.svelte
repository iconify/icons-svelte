<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm9l0rbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm9l0rbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-3-ai-line" {...props}></Icon>
