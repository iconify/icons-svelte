<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bg8i-6qpe.css';
import '../../css/a/a2dqemwrc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtVNFwewy"><g class="v3_i3wktz"><path class="bg8i-6qpe"/><path class="a2dqemwrc"/></g></mask></defs><path mask="url(#SVGtVNFwewy)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:contrast-view" {...props}></Icon>
