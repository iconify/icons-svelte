<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se-3hvqef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se-3hvqef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-marker-outline" {...props}></Icon>
