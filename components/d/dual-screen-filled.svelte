<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svh0msb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svh0msb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dual-screen-filled" {...props}></Icon>
