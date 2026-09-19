<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu5cfjbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":256};
const content = `<path class="vu5cfjbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:digital-dot" {...props}></Icon>
