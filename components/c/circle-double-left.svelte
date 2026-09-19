<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/y/yfrru90nb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3GkUwb1U"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="yfrru90nb"/></g></mask></defs><path mask="url(#SVG3GkUwb1U)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:circle-double-left" {...props}></Icon>
