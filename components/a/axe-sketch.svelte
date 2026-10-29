<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cend-5brl.css';
import '../../css/x/xzsn8_b-l.css';
import '../../css/m/m-ibzdb4g.css';
import '../../css/x/x76bqtbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cend-5brl"/><path class="wm-k xzsn8_b-l"/><path class="m-ibzdb4g wm-k"/><path class="wm-a x76bqtbvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:axe-sketch" {...props}></Icon>
