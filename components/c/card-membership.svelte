<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4b9_fbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="k4b9_fbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:card-membership" {...props}></Icon>
