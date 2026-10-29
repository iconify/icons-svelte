<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n7zpq9she.css';
import '../../css/r/rpg-511wd.css';
import '../../css/r/rzdv-tbps.css';
import '../../css/o/o2m0gts_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n7zpq9she"/><path class="rpg-511wd wm-k"/><path class="rzdv-tbps wm-k"/><path class="o2m0gts_u wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gallery-horizontal-sketch" {...props}></Icon>
