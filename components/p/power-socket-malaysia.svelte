<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcsg_ybgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcsg_ybgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-socket-malaysia" {...props}></Icon>
