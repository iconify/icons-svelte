<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sll_zg-uo.css';
import '../../css/k/k2249mt9o.css';
import '../../css/v/v9u8nhb5n.css';
import '../../css/t/tder15a4e.css';
import '../../css/m/me658039f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<radialGradient id="SVGShLqnd6n" cx="256" cy="256" r="247.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="sll_zg-uo"/><stop offset=".853" class="k2249mt9o"/><stop offset="1" class="v9u8nhb5n"/></radialGradient><path fill="url(#SVGShLqnd6n)" class="tder15a4e"/><path class="me658039f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gerbera-dark" {...props}></Icon>
