<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/ksm-3clzv.css';
import '../../css/s/sdaucgb_l.css';
import '../../css/h/h-u5cozqr.css';
import '../../css/x/xpwipybon.css';
import '../../css/f/fxix_iiqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ksm-3clzv wm-deco"/><path class="sdaucgb_l wm-deco"/><path class="h-u5cozqr wm-k"/><path class="wm-a xpwipybon"/><path class="fxix_iiqi wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-lock-blueprint" {...props}></Icon>
