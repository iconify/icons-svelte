<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/beq2bq-ru.css';
import '../../css/g/gitu83bla.css';
import '../../css/a/azlmfgbpz.css';
import '../../css/v/vu-t8mz1s.css';
import '../../css/i/idh12yb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="beq2bq-ru wm-k"/><path class="gitu83bla wm-shadow"/><path class="azlmfgbpz wm-k"/><path class="vu-t8mz1s wm-k"/><path class="idh12yb8z wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:house-plus-engrave" {...props}></Icon>
