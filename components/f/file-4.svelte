<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp5dk7q3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rp5dk7q3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:file-4" {...props}></Icon>
