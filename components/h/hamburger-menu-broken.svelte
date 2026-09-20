<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/h4yzaxyri.css';
import '../../css/z/zht_dpbhk.css';
import '../../css/z/zj3_xl2hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h4yzaxyri"/><path class="zht_dpbhk"/><path class="zj3_xl2hb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hamburger-menu-broken" {...props}></Icon>
