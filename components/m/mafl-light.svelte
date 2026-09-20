<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3e7nvr4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m3e7nvr4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mafl-light" {...props}></Icon>
