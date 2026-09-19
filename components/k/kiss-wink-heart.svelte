<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/h/h06k64bje.css';
import '../../css/g/gdem_rh5e.css';
import '../../css/w/w487obc3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="h06k64bje"/><path class="gdem_rh5e"/><path class="w487obc3p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:kiss-wink-heart" {...props}></Icon>
