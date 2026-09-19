<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kca82-bbm.css';
import '../../css/p/pl_657gxa.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFawpXbsf"><g class="v3_i3wktz"><path class="kca82-bbm"/><path class="pl_657gxa"/></g></mask></defs><path mask="url(#SVGFawpXbsf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:map-road" {...props}></Icon>
