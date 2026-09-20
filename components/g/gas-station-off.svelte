<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te31bcj7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te31bcj7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gas-station-off" {...props}></Icon>
