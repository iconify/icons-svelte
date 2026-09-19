<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc0v658tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":432};
const content = `<path class="gc0v658tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:male-female" {...props}></Icon>
