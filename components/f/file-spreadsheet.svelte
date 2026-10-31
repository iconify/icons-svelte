<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o31ue_bnk.css';
import '../../css/x/xo92ezbpx.css';
import '../../css/p/p9ft05bsh.css';
import '../../css/j/jksjufbtm.css';
import '../../css/u/u7l_q6bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o31ue_bnk wm-k"/><path class="wm-shine xo92ezbpx"/><path class="p9ft05bsh wm-shine"/><path class="jksjufbtm wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:file-spreadsheet" {...props}></Icon>
