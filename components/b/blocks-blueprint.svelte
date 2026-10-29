<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/sx2o51k2m.css';
import '../../css/d/dt-dc1j3v.css';
import '../../css/m/m_6pf-bvu.css';
import '../../css/v/vyzg3stsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="sx2o51k2m wm-deco"/><path class="dt-dc1j3v wm-deco"/><path class="m_6pf-bvu wm-k"/><path class="vyzg3stsl wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:blocks-blueprint" {...props}></Icon>
