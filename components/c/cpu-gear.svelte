<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmx1c8box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmx1c8box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cpu-gear" {...props}></Icon>
