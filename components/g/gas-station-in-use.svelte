<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xijb7ktck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xijb7ktck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gas-station-in-use" {...props}></Icon>
