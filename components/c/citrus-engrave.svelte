<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wj-_vp29w.css';
import '../../css/w/wrmxp3bja.css';
import '../../css/e/eug742r3l.css';
import '../../css/w/wabd8kb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wj-_vp29w wm-k"/><path class="wm-shadow wrmxp3bja"/><path class="eug742r3l wm-k"/><path class="wabd8kb8q wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:citrus-engrave" {...props}></Icon>
