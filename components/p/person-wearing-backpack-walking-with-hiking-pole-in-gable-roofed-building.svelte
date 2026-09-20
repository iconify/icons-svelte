<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eowlsrbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eowlsrbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-backpack-walking-with-hiking-pole-in-gable-roofed-building" {...props}></Icon>
