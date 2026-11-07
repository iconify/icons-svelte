<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/prxmevb8y.css';
import '../../css/q/qvktbkbmj.css';
import '../../css/x/xmrhfhb4m.css';
import '../../css/v/v2s8-khye.css';
import '../../css/i/ij65dz6ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="prxmevb8y"/><path class="qvktbkbmj"/><path class="xmrhfhb4m"/><path class="v2s8-khye"/><path class="ij65dz6ik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:backpack-line-duotone" {...props}></Icon>
