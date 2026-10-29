<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/huw4-tbyz.css';
import '../../css/x/xv4sdqbgf.css';
import '../../css/o/o-fwz22nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="huw4-tbyz"/><path class="wm-shadow xv4sdqbgf"/><path class="o-fwz22nq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-dashed-engrave" {...props}></Icon>
