<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1_swcb_o.css';
import '../../css/q/qgei9b-2x.css';
import '../../css/q/qd28qqumi.css';
import '../../css/n/nzo8xybpk.css';
import '../../css/w/wb2xu6o9b.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVGDdAdLq"><g class="v1_swcb_o"><circle class="qgei9b-2x"/><circle class="qd28qqumi"/><circle class="nzo8xybpk"/><circle class="wb2xu6o9b"/></g></mask></defs><path mask="url(#SVGVGDdAdLq)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:application-two" {...props}></Icon>
