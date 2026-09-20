<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3xtuk_0z.css';
import '../../css/h/hs96w8b5o.css';
import '../../css/v/vdfc60r-c.css';
import '../../css/a/ala74cbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="hs96w8b5o"/><path class="vdfc60r-c"/><path class="ala74cbvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:location-map" {...props}></Icon>
