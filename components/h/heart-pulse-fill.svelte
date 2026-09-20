<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb2wu4hat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb2wu4hat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:heart-pulse-fill" {...props}></Icon>
