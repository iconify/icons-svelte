<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ah34vx61k.css';
import '../../css/u/uxs6sac8y.css';
import '../../css/i/ielwengza.css';
import '../../css/z/zhtgx2bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ah34vx61k wm-k"/><path class="uxs6sac8y wm-k"/><path class="ielwengza wm-k"/><path class="wm-a zhtgx2bwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:network-sketch" {...props}></Icon>
