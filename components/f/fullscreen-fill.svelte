<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0vm8o8_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0vm8o8_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:fullscreen-fill" {...props}></Icon>
