<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/v/vihc9mssv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVQ9zscQF"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="vihc9mssv"/></g></mask></defs><path mask="url(#SVGVQ9zscQF)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:grinning-face-with-squinting-eyes" {...props}></Icon>
