<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xdm0-sb7l.css';
import '../../css/y/yd5ssobgf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwWf9HgGd"><g class="v3_i3wktz"><path class="xdm0-sb7l"/><path clip-rule="evenodd" class="yd5ssobgf"/></g></mask></defs><path mask="url(#SVGwWf9HgGd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:hand-left" {...props}></Icon>
