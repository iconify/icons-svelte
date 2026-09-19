<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p_gv6ibcq.css';
import '../../css/v/v0m5xdb6q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<mask id="svgIDb"><g class="ft5dv1b6b"><g clip-path="url(#svgIDa)"><path class="p_gv6ibcq"/></g><defs><clipPath id="svgIDa"><path class="v0m5xdb6q"/></clipPath></defs></g></mask><path mask="url(#svgIDb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:a-cane" {...props}></Icon>
