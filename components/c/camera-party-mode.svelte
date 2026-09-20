<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne86bmo9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne86bmo9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-party-mode" {...props}></Icon>
