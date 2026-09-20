<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl5xgp-7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl5xgp-7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camera-2-ai-line" {...props}></Icon>
