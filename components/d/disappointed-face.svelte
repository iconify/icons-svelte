<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/x/xvhswr2cp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIgpm3gvp"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="xvhswr2cp"/></g></mask></defs><path mask="url(#SVGIgpm3gvp)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:disappointed-face" {...props}></Icon>
