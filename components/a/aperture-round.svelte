<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feu6ydgps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feu6ydgps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:aperture-round" {...props}></Icon>
