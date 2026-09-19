<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/k/ktnx_7-or.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3Ccl1LrK"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="ktnx_7-or"/></g></mask></defs><path mask="url(#SVG3Ccl1LrK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:down-c" {...props}></Icon>
