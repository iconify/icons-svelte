<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5dw_9pvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5dw_9pvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-square" {...props}></Icon>
