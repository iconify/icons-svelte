<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en0dpotxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en0dpotxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:buoy-filled" {...props}></Icon>
