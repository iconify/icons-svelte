<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-c80ro0i.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/p/p8243xb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGdPWX3cZz" x1="256" x2="256" y1="512" y2="0" gradientUnits="userSpaceOnUse"><stop offset="0" class="f-c80ro0i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGdPWX3cZz)" class="p8243xb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fastgpt-light" {...props}></Icon>
