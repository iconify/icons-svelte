<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/v/vces4wbou.css';
import '../../css/f/fb_51sb_m.css';
import '../../css/j/jxsnms7hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="vces4wbou"/><circle class="fb_51sb_m"/><path class="jxsnms7hz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:division" {...props}></Icon>
