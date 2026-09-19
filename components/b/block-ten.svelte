<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adexpl72i.css';
import '../../css/d/d70u10bbk.css';
import '../../css/d/dov8vg2gk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIngd6caS"><g class="adexpl72i"><path class="d70u10bbk"/><path class="dov8vg2gk"/></g></mask></defs><path mask="url(#SVGIngd6caS)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:block-ten" {...props}></Icon>
