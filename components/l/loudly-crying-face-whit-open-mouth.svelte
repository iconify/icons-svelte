<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/e/eh2-i3ale.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8xPXIdjS"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="eh2-i3ale"/></g></mask></defs><path mask="url(#SVG8xPXIdjS)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:loudly-crying-face-whit-open-mouth" {...props}></Icon>
