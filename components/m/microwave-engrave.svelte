<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mi7v5hbvw.css';
import '../../css/a/ai5q-kbba.css';
import '../../css/t/t8-4j7c2p.css';
import '../../css/x/xww6dnqya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mi7v5hbvw wm-k"/><path class="ai5q-kbba wm-shadow"/><path class="t8-4j7c2p wm-k"/><path class="wm-a xww6dnqya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:microwave-engrave" {...props}></Icon>
