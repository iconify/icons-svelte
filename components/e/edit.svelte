<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/x3u46_gnm.css';
import '../../css/a/aqj7hfbjq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoYDnedpV"><g class="v3_i3wktz"><path class="x3u46_gnm"/><path class="aqj7hfbjq"/></g></mask></defs><path mask="url(#SVGoYDnedpV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:edit" {...props}></Icon>
