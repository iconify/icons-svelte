<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v3c0odnjd.css';
import '../../css/g/gwpevo8qp.css';
import '../../css/o/o0m_us_lw.css';
import '../../css/r/rqi-mcbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v3c0odnjd"/><path class="gwpevo8qp wm-k"/><path class="o0m_us_lw wm-k"/><path class="rqi-mcbpo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:megaphone-sketch" {...props}></Icon>
