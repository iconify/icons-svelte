<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/b/blna7_bzy.css';
import '../../css/p/pqhat2p9w.css';
import '../../css/m/m0k56ib_g.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGn8eDybEM"><g class="ufeehvblu"><path class="blna7_bzy"/><path class="pqhat2p9w"/><path class="m0k56ib_g"/></g></mask></defs><path mask="url(#SVGn8eDybEM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:expand-left" {...props}></Icon>
