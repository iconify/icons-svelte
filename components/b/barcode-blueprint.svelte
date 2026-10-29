<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/x/x49uqwbjn.css';
import '../../css/b/brfohtb0o.css';
import '../../css/o/oun623fgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco x49uqwbjn"/><path class="brfohtb0o wm-deco"/><path class="oun623fgc wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:barcode-blueprint" {...props}></Icon>
