<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvtfu18_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rvtfu18_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lighthouse" {...props}></Icon>
