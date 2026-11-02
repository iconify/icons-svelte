<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipu02zq8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipu02zq8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-3-ai-fill" {...props}></Icon>
