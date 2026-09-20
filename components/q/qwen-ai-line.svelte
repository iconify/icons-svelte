<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkl9bwb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkl9bwb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:qwen-ai-line" {...props}></Icon>
