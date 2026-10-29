<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/iacwg347f.css';
import '../../css/b/bxjv56brc.css';
import '../../css/z/znxjuv-vy.css';
import '../../css/z/z11iafbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="iacwg347f wm-deco"/><path class="bxjv56brc wm-deco"/><path class="znxjuv-vy"/><path class="z11iafbez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:minimize-2-blueprint" {...props}></Icon>
