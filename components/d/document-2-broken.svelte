<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dxplmnb3y.css';
import '../../css/x/xn4zvpbmt.css';
import '../../css/p/pyeja5bvq.css';
import '../../css/x/xj93a5bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dxplmnb3y"/><path class="xn4zvpbmt"/><path class="pyeja5bvq"/><path class="xj93a5bgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-2-broken" {...props}></Icon>
