<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuv8jpbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuv8jpbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:map-pins" {...props}></Icon>
