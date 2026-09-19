<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bgr4__y9v.css';
import '../../css/u/upf9j8dhv.css';
import '../../css/q/qiacie2ce.css';
import '../../css/l/l0y6kqsdf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOL58XdYm"><g class="v3_i3wktz"><path class="bgr4__y9v"/><rect class="upf9j8dhv"/><rect class="qiacie2ce"/><path class="l0y6kqsdf"/></g></mask></defs><path mask="url(#SVGOL58XdYm)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:city-one" {...props}></Icon>
