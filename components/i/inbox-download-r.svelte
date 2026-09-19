<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/d/d_3n8jz2q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpsPjrdxI"><g class="v3_i3wktz"><rect class="h9qj9o6mz"/><path class="d_3n8jz2q"/></g></mask></defs><path mask="url(#SVGpsPjrdxI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:inbox-download-r" {...props}></Icon>
