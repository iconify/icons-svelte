<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmyw_-b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmyw_-b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-ai-fill" {...props}></Icon>
