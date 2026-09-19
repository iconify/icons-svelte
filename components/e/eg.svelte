<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/e/e3s0is8tx.css';
import '../../css/u/ug0o9qbnm.css';
import '../../css/v/vwsqgnj8x.css';
import '../../css/r/r3ij0x-wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="e3s0is8tx"/><path class="ug0o9qbnm"/><path class="vwsqgnj8x"/><path class="r3ij0x-wy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:eg" {...props}></Icon>
