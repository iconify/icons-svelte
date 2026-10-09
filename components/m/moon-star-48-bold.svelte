<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faamz_bdw.css';
import '../../css/u/uv8trf44e.css';
import '../../css/b/bswze6tia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="faamz_bdw"/><path class="uv8trf44e"/><path class="bswze6tia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-star-48-bold" {...props}></Icon>
