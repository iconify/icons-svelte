<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m_-dhfbtd.css';
import '../../css/h/hanoadvko.css';
import '../../css/u/uh01hzbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m_-dhfbtd"/><path class="hanoadvko wm-shadow"/><path class="uh01hzbyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-engrave" {...props}></Icon>
