<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k71kedpaw.css';
import '../../css/k/krer2skwe.css';
import '../../css/t/tq6-pqdhd.css';
import '../../css/b/b88gxzbev.css';
import '../../css/i/iib4vtwgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k71kedpaw wm-k"/><path class="krer2skwe wm-a"/><path class="tq6-pqdhd wm-shadow"/><path class="b88gxzbev wm-k"/><path class="iib4vtwgi wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:radio-tower-engrave" {...props}></Icon>
