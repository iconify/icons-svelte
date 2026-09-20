<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp8a636dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gp8a636dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-music-stand-light" {...props}></Icon>
