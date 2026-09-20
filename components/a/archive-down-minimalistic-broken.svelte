<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p5qbbdc2d.css';
import '../../css/b/bq64z4bfb.css';
import '../../css/e/e1dpahbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p5qbbdc2d"/><path class="bq64z4bfb"/><path class="e1dpahbxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-down-minimalistic-broken" {...props}></Icon>
