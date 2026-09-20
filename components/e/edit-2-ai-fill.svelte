<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0lp7-bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0lp7-bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-2-ai-fill" {...props}></Icon>
