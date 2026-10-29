<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dqi4ifb3t.css';
import '../../css/n/n-n2__xqz.css';
import '../../css/s/skgel1llp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dqi4ifb3t"/><path class="n-n2__xqz wm-shadow"/><path class="skgel1llp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:playground-engrave" {...props}></Icon>
