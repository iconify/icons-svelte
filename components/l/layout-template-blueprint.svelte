<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vpvtycafa.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/q/qn8vmzhwm.css';
import '../../css/f/frcn26bwv.css';
import '../../css/k/k4v78ybpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vpvtycafa wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="qn8vmzhwm wm-k"/><path class="frcn26bwv wm-a"/><path class="k4v78ybpm wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:layout-template-blueprint" {...props}></Icon>
