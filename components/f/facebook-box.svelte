<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfdus8bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="lfdus8bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:facebook-box" {...props}></Icon>
