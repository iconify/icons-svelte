<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f661euvzn.css';
import '../../css/j/j---ejbcs.css';
import '../../css/j/jfb-yjbgw.css';
import '../../css/q/qaz17vbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f661euvzn"/><path class="j---ejbcs wm-shadow"/><path class="jfb-yjbgw"/><path class="qaz17vbsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:book-engrave" {...props}></Icon>
