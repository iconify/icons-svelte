<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhgi928af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhgi928af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hexagons-fill" {...props}></Icon>
