<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaknn7bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaknn7bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:music-2-ai-fill" {...props}></Icon>
