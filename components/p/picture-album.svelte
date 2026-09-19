<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/i/i5misbc2b.css';
import '../../css/w/wbasp_ynt.css';
import '../../css/w/wp3pith5r.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBCL8Dd5y"><g class="v3_i3wktz"><rect class="i5misbc2b"/><path class="wbasp_ynt"/><path class="wp3pith5r"/></g></mask></defs><path mask="url(#SVGBCL8Dd5y)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:picture-album" {...props}></Icon>
