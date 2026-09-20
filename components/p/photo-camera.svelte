<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rafffx2tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rafffx2tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:photo-camera" {...props}></Icon>
