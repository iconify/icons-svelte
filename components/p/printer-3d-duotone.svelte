<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rrbcwybsn.css';
import '../../css/x/xci45cnkx.css';
import '../../css/s/s585j5b6i.css';
import '../../css/s/s78wgswbm.css';
import '../../css/q/qyj_m3jrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rrbcwybsn"/><path class="xci45cnkx"/><path class="s585j5b6i"/><path class="s78wgswbm"/><path class="qyj_m3jrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:printer-3d-duotone" {...props}></Icon>
