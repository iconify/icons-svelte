<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/f/f5758gbbz.css';
import '../../css/u/uowmflbel.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSes5ne2H"><g class="ufeehvblu"><path class="f5758gbbz"/><path class="uowmflbel"/></g></mask></defs><path mask="url(#SVGSes5ne2H)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:preview-open" {...props}></Icon>
