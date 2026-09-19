<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dv-67s2rc.css';
import '../../css/s/sxmwz_82x.css';
import '../../css/m/mdlrplbcn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG36y0sc2l"><g class="v3_i3wktz"><path class="dv-67s2rc"/><path class="sxmwz_82x"/><path class="mdlrplbcn"/></g></mask></defs><path mask="url(#SVG36y0sc2l)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:calendar" {...props}></Icon>
