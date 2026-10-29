<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/f4cf7nb4b.css';
import '../../css/s/sdaucgb_l.css';
import '../../css/h/h-u5cozqr.css';
import '../../css/z/zwefmf5hz.css';
import '../../css/f/fxix_iiqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="f4cf7nb4b wm-deco"/><path class="sdaucgb_l wm-deco"/><path class="h-u5cozqr wm-k"/><path class="wm-a zwefmf5hz"/><path class="fxix_iiqi wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-question-blueprint" {...props}></Icon>
