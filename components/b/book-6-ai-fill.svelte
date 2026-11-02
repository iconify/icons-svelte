<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hev68328m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hev68328m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-6-ai-fill" {...props}></Icon>
