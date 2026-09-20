<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m78btob1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m78btob1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-in-gable-roofed-shelter" {...props}></Icon>
