<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e2hwfubct.css';
import '../../css/l/l-cphhs4g.css';
import '../../css/z/zl-i7yb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e2hwfubct"/><path class="l-cphhs4g wm-shadow"/><path class="zl-i7yb9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:close-engrave" {...props}></Icon>
