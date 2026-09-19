<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/c/c8elt-b4t.css';
import '../../css/y/yq1t-4wqr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGX2vPLd3a"><g class="aql7dnt-u"><path class="c8elt-b4t"/><path class="yq1t-4wqr"/></g></mask></defs><path mask="url(#SVGX2vPLd3a)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:circle-house" {...props}></Icon>
