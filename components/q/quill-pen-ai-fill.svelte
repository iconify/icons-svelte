<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhj5f0b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhj5f0b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quill-pen-ai-fill" {...props}></Icon>
