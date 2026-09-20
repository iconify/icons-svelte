<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl1x_9bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl1x_9bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ball-pen-line" {...props}></Icon>
