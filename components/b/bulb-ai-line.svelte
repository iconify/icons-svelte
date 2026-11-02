<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zicn2_zap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zicn2_zap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bulb-ai-line" {...props}></Icon>
