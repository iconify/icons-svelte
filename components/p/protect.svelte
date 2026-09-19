<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/gj7m2tbbh.css';
import '../../css/o/omd-qi_-c.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGM7aMbcQo"><g class="v3_i3wktz"><path class="gj7m2tbbh"/><path class="omd-qi_-c"/></g></mask></defs><path mask="url(#SVGM7aMbcQo)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:protect" {...props}></Icon>
