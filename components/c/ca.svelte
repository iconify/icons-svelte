<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/f/fcz6x7bej.css';
import '../../css/d/d6o5xabkp.css';
import '../../css/p/pi4o_73rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="fcz6x7bej"/><path class="d6o5xabkp"/><path class="pi4o_73rm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:ca" {...props}></Icon>
