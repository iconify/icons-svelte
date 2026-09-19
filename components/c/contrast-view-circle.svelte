<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/y/yir80ubeq.css';
import '../../css/d/di4e5317x.css';
import '../../css/i/i65qn8syi.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7qtXDcUx"><g class="v3_i3wktz"><path clip-rule="evenodd" class="yir80ubeq"/><path class="di4e5317x"/><path class="i65qn8syi"/></g></mask></defs><path mask="url(#SVG7qtXDcUx)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:contrast-view-circle" {...props}></Icon>
