<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh0bafb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nh0bafb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:extension-puzzle-sharp" {...props}></Icon>
