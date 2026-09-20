<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anh6pktus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anh6pktus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-confused" {...props}></Icon>
