<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqhdcmbrc.css';
import '../../css/a/aemqdzbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oqhdcmbrc"/><path class="aemqdzbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-off-20-bold" {...props}></Icon>
