<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5qz3lb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5qz3lb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:landscape-ai-line" {...props}></Icon>
