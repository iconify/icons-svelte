<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q66nwbcvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q66nwbcvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chat-01" {...props}></Icon>
