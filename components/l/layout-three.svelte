<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/q/qzux5j50o.css';
import '../../css/d/doz9sd1gv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGarAxqcel"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="qzux5j50o"/><path class="doz9sd1gv"/></g></mask></defs><path mask="url(#SVGarAxqcel)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:layout-three" {...props}></Icon>
