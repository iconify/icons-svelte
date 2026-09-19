<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ig1fb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p7ig1fb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pulse" {...props}></Icon>
