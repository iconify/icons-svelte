<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x59j0j2-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x59j0j2-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:microscope-solid" {...props}></Icon>
