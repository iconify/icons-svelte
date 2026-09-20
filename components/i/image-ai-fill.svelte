<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr7da2brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr7da2brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-ai-fill" {...props}></Icon>
