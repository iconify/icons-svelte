<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/l9hcfvb2t.css';
import '../../css/u/uqe17tcka.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnxiyGcFt"><g class="aql7dnt-u"><path class="l9hcfvb2t"/><path class="uqe17tcka"/></g></mask></defs><path mask="url(#SVGnxiyGcFt)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:foursquare" {...props}></Icon>
