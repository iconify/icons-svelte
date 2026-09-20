<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhwehbwty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhwehbwty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-2-ai-line" {...props}></Icon>
