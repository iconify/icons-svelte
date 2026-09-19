<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/ys67npbsn.css';
import '../../css/x/xfswdop-m.css';
import '../../css/x/xtbnnobia.css';
import '../../css/n/nzuotib9e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRBQrpehk"><g class="s9cl3zbei"><path class="ys67npbsn"/><path class="xfswdop-m"/><path class="xtbnnobia"/><path class="nzuotib9e"/></g></mask></defs><path mask="url(#SVGRBQrpehk)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:baggage-delay" {...props}></Icon>
