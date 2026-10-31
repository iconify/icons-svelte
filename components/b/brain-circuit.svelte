<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/m/m_n5q72bc.css';
import '../../css/z/z_6ptwbhl.css';
import '../../css/d/d_i46k63m.css';
import '../../css/w/wm1y2mbyi.css';
import '../../css/v/v3bzhxbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="m_n5q72bc"/><path class="wm-shine z_6ptwbhl"/><path class="d_i46k63m wm-k"/><path class="wm-a wm1y2mbyi"/><path class="v3bzhxbbh wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:brain-circuit" {...props}></Icon>
