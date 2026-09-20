<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/u/u27udoylh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGSrlvhdAD" x1="0" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGSrlvhdAD)" class="u27udoylh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:folderhost-light" {...props}></Icon>
