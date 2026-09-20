<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb4p4fbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb4p4fbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:lightbulb-ai-line" {...props}></Icon>
