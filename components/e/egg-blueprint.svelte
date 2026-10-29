<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/e/eoyw7hy5h.css';
import '../../css/a/a92mxccrf.css';
import '../../css/n/nip8kwy2i.css';
import '../../css/o/o31m35bod.css';
import '../../css/t/t_iyb2b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="eoyw7hy5h wm-deco"/><path class="a92mxccrf wm-deco"/><path class="nip8kwy2i wm-deco"/><path class="o31m35bod wm-k"/><path class="t_iyb2b1h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:egg-blueprint" {...props}></Icon>
