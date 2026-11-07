<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/prxmevb8y.css';
import '../../css/p/pzh9jhb6y.css';
import '../../css/d/dfwvprboi.css';
import '../../css/v/v2s8-khye.css';
import '../../css/v/vn59_jbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="prxmevb8y"/><path class="pzh9jhb6y"/><path class="dfwvprboi"/><path class="v2s8-khye"/><path class="vn59_jbgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:backpack-linear" {...props}></Icon>
