<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gkbo53bao.css';
import '../../css/j/jd6nm6b1y.css';
import '../../css/v/vwl3tqb1n.css';
import '../../css/d/dhjh0zb6s.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaYcmNdPN"><g class="ft5dv1b6b"><path clip-rule="evenodd" class="gkbo53bao"/><path class="jd6nm6b1y"/><path class="vwl3tqb1n"/><path class="dhjh0zb6s"/></g></mask></defs><path mask="url(#SVGaYcmNdPN)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:composition" {...props}></Icon>
