<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/nxj9c8cpq.css';
import '../../css/t/ty4d2jlgr.css';
import '../../css/h/h1vo1h1bn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG88OrNbFr"><g class="v3_i3wktz"><path class="nxj9c8cpq"/><path class="ty4d2jlgr"/><path class="h1vo1h1bn"/></g></mask></defs><path mask="url(#SVG88OrNbFr)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:coordinate-system" {...props}></Icon>
