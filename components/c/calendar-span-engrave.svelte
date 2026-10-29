<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hlrr2hb3k.css';
import '../../css/j/jalfqco1n.css';
import '../../css/a/aari1qi6v.css';
import '../../css/j/jmvv3kbnk.css';
import '../../css/j/j0cuxet1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hlrr2hb3k wm-k"/><path class="jalfqco1n wm-a"/><path class="aari1qi6v wm-shadow"/><path class="jmvv3kbnk wm-k"/><path class="j0cuxet1l wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-span-engrave" {...props}></Icon>
