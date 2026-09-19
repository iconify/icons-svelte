<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up5sddcmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="up5sddcmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:card-sim" {...props}></Icon>
