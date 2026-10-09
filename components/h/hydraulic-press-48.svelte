<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce0984b4t.css';
import '../../css/t/tetsfk0bz.css';
import '../../css/w/wl07m1b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ce0984b4t"/><path class="tetsfk0bz"/><path class="wl07m1b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydraulic-press-48" {...props}></Icon>
