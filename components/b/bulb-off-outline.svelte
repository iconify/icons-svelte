<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0z391zni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0z391zni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bulb-off-outline" {...props}></Icon>
