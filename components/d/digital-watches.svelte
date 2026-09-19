<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/qbdhy6b-y.css';
import '../../css/z/z7cxaabsm.css';
import '../../css/z/z6hebhb_q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCXg50bGl"><g class="s9cl3zbei"><rect class="qbdhy6b-y"/><path class="z7cxaabsm"/><path class="z6hebhb_q"/></g></mask></defs><path mask="url(#SVGCXg50bGl)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:digital-watches" {...props}></Icon>
