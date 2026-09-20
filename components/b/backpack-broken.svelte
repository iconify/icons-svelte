<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d76br_vtg.css';
import '../../css/p/pzh9jhb6y.css';
import '../../css/a/a6lfmac3o.css';
import '../../css/h/h8wqmtb6z.css';
import '../../css/v/vn59_jbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d76br_vtg"/><path class="pzh9jhb6y"/><path class="a6lfmac3o"/><path class="h8wqmtb6z"/><path class="vn59_jbgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:backpack-broken" {...props}></Icon>
