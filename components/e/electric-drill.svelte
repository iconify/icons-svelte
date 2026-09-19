<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/mqe9jgjyr.css';
import '../../css/w/wqyxkuyuv.css';
import '../../css/a/a4soon8wk.css';
import '../../css/i/izth8wb4y.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlbNZIdvN"><g class="v3_i3wktz"><path class="mqe9jgjyr"/><path class="wqyxkuyuv"/><path class="a4soon8wk"/><path class="izth8wb4y"/></g></mask></defs><path mask="url(#SVGlbNZIdvN)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:electric-drill" {...props}></Icon>
