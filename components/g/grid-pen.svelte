<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry89rcb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ry89rcb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:grid-pen" {...props}></Icon>
