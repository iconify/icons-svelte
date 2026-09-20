<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez8rbaciu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ez8rbaciu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-backpack-walking-with-hiking-pole-in-gable-roofed-shelter" {...props}></Icon>
