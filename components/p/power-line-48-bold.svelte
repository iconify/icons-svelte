<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x32ukaqaa.css';
import '../../css/i/ivrs2fbio.css';
import '../../css/v/veyr_t3yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x32ukaqaa"/><path class="ivrs2fbio"/><path class="veyr_t3yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-line-48-bold" {...props}></Icon>
