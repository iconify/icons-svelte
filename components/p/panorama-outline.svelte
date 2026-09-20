<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/islj7dbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="islj7dbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:panorama-outline" {...props}></Icon>
