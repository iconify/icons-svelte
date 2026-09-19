<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/p89m2obdw.css';
import '../../css/c/cjfecbceb.css';
import '../../css/s/szmwbtbmw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhB20hcQf"><g class="v3_i3wktz"><path class="p89m2obdw"/><path class="cjfecbceb"/><path clip-rule="evenodd" class="szmwbtbmw"/></g></mask></defs><path mask="url(#SVGhB20hcQf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:financing-one" {...props}></Icon>
