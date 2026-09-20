<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-c80ro0i.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/u/udnwifidc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGb01JPbTh" x1="256" x2="256" y1="-.75" y2="511.25" gradientUnits="userSpaceOnUse"><stop offset="0" class="f-c80ro0i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGb01JPbTh)" class="udnwifidc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:app-store-light" {...props}></Icon>
