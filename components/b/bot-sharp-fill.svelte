<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/kdybctn7p.css';
import '../../css/d/drs9macuz.css';
import '../../css/s/sp3ujwwyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kdybctn7p"/><path class="drs9macuz"/><path class="sp3ujwwyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bot-sharp-fill" {...props}></Icon>
