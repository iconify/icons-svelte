<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unnecvo7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unnecvo7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:closed-captioning-ai-fill" {...props}></Icon>
