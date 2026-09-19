<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/ff066bcmc.css';
import '../../css/w/wrlqzdago.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAGAFydaD"><g class="aql7dnt-u"><path class="ff066bcmc"/><path class="wrlqzdago"/></g></mask></defs><path mask="url(#SVGAGAFydaD)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:map-draw" {...props}></Icon>
