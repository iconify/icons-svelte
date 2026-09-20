<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj6a84bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj6a84bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-play" {...props}></Icon>
