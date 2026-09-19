<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0a2_b5uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r0a2_b5uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bosque" {...props}></Icon>
