<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4t-c-b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4t-c-b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:arduino-dark" {...props}></Icon>
