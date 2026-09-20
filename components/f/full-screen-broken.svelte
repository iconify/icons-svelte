<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x-1lf64uh.css';
import '../../css/a/apdq1ub8p.css';
import '../../css/r/ros5bvrws.css';
import '../../css/z/ztbmtjbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x-1lf64uh"/><path class="apdq1ub8p"/><path class="ros5bvrws"/><path class="ztbmtjbiz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:full-screen-broken" {...props}></Icon>
