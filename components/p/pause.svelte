<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt43jbb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="yt43jbb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pause" {...props}></Icon>
