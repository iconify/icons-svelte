<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne7p8x31a.css';
import '../../css/f/fohdu3hry.css';
import '../../css/f/fp6ugybfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ne7p8x31a"/><path class="fohdu3hry"/><path class="fp6ugybfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:id-management" {...props}></Icon>
