<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oh_e7zb2w.css';
import '../../css/w/wdi0syhdo.css';
import '../../css/u/ul5gnlx5m.css';
import '../../css/q/qodtiuben.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRkQAljxN"><g class="ufeehvblu"><path class="oh_e7zb2w"/><path class="wdi0syhdo"/><path class="ul5gnlx5m"/><ellipse class="qodtiuben"/></g></mask></defs><path mask="url(#SVGRkQAljxN)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:ipo" {...props}></Icon>
