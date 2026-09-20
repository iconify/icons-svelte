<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa1n06c0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa1n06c0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-off" {...props}></Icon>
