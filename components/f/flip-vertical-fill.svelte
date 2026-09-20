<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm5nsnb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm5nsnb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flip-vertical-fill" {...props}></Icon>
