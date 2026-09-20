<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsm7hzbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsm7hzbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:access-point-off" {...props}></Icon>
