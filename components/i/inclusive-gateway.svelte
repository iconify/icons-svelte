<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lhob5rbnu.css';
import '../../css/u/uiygcpbmv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPZeTfe3m"><g class="ufeehvblu"><path class="lhob5rbnu"/><path class="uiygcpbmv"/></g></mask></defs><path mask="url(#SVGPZeTfe3m)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:inclusive-gateway" {...props}></Icon>
