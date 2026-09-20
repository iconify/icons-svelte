<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm95ujemq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm95ujemq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:movie-2-ai-line" {...props}></Icon>
