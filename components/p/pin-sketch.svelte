<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x5tr0cc0q.css';
import '../../css/q/qmcm-kbhi.css';
import '../../css/p/ppo49n8pg.css';
import '../../css/t/txm-rabnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="x5tr0cc0q"/><path class="qmcm-kbhi wm-a"/><path class="ppo49n8pg wm-k"/><path class="txm-rabnp wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pin-sketch" {...props}></Icon>
