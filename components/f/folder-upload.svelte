<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xedzjig2g.css';
import '../../css/m/mh8w0dbxt.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAbbVvc7Y"><g class="v3_i3wktz"><path class="xedzjig2g"/><path class="mh8w0dbxt"/></g></mask></defs><path mask="url(#SVGAbbVvc7Y)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:folder-upload" {...props}></Icon>
