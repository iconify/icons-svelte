<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfoyxdpod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="sfoyxdpod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flickr-before" {...props}></Icon>
