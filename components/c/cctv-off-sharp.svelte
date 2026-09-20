<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt6y7e71h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt6y7e71h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cctv-off-sharp" {...props}></Icon>
