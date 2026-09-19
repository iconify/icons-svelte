<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xdw2bdcxa.css';
import '../../css/t/tjohlwgfv.css';
import '../../css/u/uutusgtyk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaa06Tchr"><g class="ufeehvblu"><path class="xdw2bdcxa"/><path class="tjohlwgfv"/><path class="uutusgtyk"/></g></mask></defs><path mask="url(#SVGaa06Tchr)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:creative" {...props}></Icon>
