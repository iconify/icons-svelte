<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/w/whph_o--x.css';
import '../../css/q/qdjay_j5b.css';
import '../../css/y/yveo74b2b.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWNgSieUZ"><g class="ufeehvblu"><path class="whph_o--x"/><path class="qdjay_j5b"/><path class="yveo74b2b"/></g></mask></defs><path mask="url(#SVGWNgSieUZ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:install" {...props}></Icon>
