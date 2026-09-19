<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/d/dg3mn7bsj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGj5QrybRn"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="dg3mn7bsj"/></g></mask></defs><path mask="url(#SVGj5QrybRn)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:grinning-face-with-tightly-closed-eyes-open-mouth" {...props}></Icon>
