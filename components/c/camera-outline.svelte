<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs4b5vbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs4b5vbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-outline" {...props}></Icon>
