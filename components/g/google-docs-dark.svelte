<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxk51mbgs.css';
import '../../css/p/p2k-rbb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxk51mbgs"/><path class="p2k-rbb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-docs-dark" {...props}></Icon>
