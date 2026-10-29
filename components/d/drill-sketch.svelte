<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eim7--b-x.css';
import '../../css/b/btxwm6bkt.css';
import '../../css/u/u6jpcwfqz.css';
import '../../css/y/ykgfagzcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eim7--b-x"/><path class="btxwm6bkt wm-k"/><path class="u6jpcwfqz wm-k"/><path class="wm-a ykgfagzcz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:drill-sketch" {...props}></Icon>
