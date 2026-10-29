<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q3t1b2tyl.css';
import '../../css/l/l0-s4xb5x.css';
import '../../css/g/gbftiw4sm.css';
import '../../css/r/rmqzxtb-y.css';
import '../../css/o/o2vm0kbuj.css';
import '../../css/m/m3zf-tb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q3t1b2tyl wm-k"/><path class="l0-s4xb5x wm-shadow"/><path class="gbftiw4sm wm-k"/><path class="rmqzxtb-y wm-k"/><path class="o2vm0kbuj wm-a"/><path class="m3zf-tb2g wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:projector-engrave" {...props}></Icon>
