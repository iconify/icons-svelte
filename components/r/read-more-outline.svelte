<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bumq7onsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bumq7onsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:read-more-outline" {...props}></Icon>
