<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/p/pi6fvo7zc.css';
import '../../css/q/qdrw9yaqh.css';
import '../../css/t/tea1m2b_s.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQR2TeczY"><g class="ufeehvblu"><path class="pi6fvo7zc"/><path class="qdrw9yaqh"/><path class="tea1m2b_s"/></g></mask></defs><path mask="url(#SVGQR2TeczY)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:connection-box" {...props}></Icon>
