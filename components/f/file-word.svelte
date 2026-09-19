<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/my50xkbpo.css';
import '../../css/l/lpi4_iblr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGE2U6yedw"><g class="v3_i3wktz"><path class="my50xkbpo"/><path class="lpi4_iblr"/></g></mask></defs><path mask="url(#SVGE2U6yedw)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:file-word" {...props}></Icon>
