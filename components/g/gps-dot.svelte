<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5yh1abav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="b5yh1abav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:gps-dot" {...props}></Icon>
