<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo1fhkblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":432};
const content = `<path class="fo1fhkblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:google-glass" {...props}></Icon>
