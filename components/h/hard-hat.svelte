<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/i/i46krnb5l.css';
import '../../css/h/h2i29krsh.css';
import '../../css/h/hcaie_vox.css';
import '../../css/m/mce9chbnc.css';
import '../../css/w/w49ngccqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="i46krnb5l"/><path class="h2i29krsh wm-shine"/><path class="hcaie_vox wm-k"/><path class="mce9chbnc wm-a"/><path class="w49ngccqq wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:hard-hat" {...props}></Icon>
