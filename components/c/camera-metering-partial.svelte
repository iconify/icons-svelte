<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5y7lob8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5y7lob8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-metering-partial" {...props}></Icon>
