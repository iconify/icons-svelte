<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgboy9bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgboy9bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hexagons" {...props}></Icon>
