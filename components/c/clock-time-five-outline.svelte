<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip2018xng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip2018xng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-five-outline" {...props}></Icon>
