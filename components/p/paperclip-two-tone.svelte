<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdaqwbcvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdaqwbcvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:paperclip-two-tone" {...props}></Icon>
