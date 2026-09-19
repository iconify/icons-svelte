<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvj9sbfxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pvj9sbfxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:obs-studio" {...props}></Icon>
