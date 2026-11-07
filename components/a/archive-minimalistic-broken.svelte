<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iscitzuxy.css';
import '../../css/p/p5qbbdc2d.css';
import '../../css/t/tir77voan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iscitzuxy"/><path class="p5qbbdc2d"/><path class="tir77voan"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-minimalistic-broken" {...props}></Icon>
