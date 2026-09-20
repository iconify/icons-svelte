<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l47gn9kpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l47gn9kpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-location-outline" {...props}></Icon>
