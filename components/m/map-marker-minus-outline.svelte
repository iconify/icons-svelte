<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i408sxblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i408sxblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-marker-minus-outline" {...props}></Icon>
