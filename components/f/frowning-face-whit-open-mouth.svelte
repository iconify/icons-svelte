<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/u/u6df5xh0x.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaHcRUcLK"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="u6df5xh0x"/></g></mask></defs><path mask="url(#SVGaHcRUcLK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:frowning-face-whit-open-mouth" {...props}></Icon>
