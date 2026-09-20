<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry06uk4_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry06uk4_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:periscope" {...props}></Icon>
