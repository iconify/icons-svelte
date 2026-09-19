<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkb3lbbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkb3lbbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:jellyseerr" {...props}></Icon>
