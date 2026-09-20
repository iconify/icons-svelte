<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syxhos6-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syxhos6-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:microphone-cancelled-filled" {...props}></Icon>
