<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poterobej.css';
import '../../css/g/gc9f00b9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poterobej"/><path class="gc9f00b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:microphone-off" {...props}></Icon>
