<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl_6u4_hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hl_6u4_hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-home-light" {...props}></Icon>
