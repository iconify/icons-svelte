<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3wm5xxdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3wm5xxdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hop-2-off-line" {...props}></Icon>
