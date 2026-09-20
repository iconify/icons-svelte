<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csmpox66s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="csmpox66s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pin-filled" {...props}></Icon>
