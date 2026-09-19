<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/b/b7e_qlv_s.css';
import '../../css/p/p0mk-tbae.css';
import '../../css/b/b1t58_7xb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuz93vesT"><g class="aql7dnt-u"><path class="b7e_qlv_s"/><path class="p0mk-tbae"/><path clip-rule="evenodd" class="b1t58_7xb"/></g></mask></defs><path mask="url(#SVGuz93vesT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:dashboard-car" {...props}></Icon>
