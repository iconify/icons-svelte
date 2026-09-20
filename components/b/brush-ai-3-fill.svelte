<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5bc61box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5bc61box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brush-ai-3-fill" {...props}></Icon>
