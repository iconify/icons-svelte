<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd9m3dh5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd9m3dh5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrange-send-backward" {...props}></Icon>
