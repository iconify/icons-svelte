<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/drxk66foz.css';
import '../../css/t/toaaljiww.css';
import '../../css/v/v2ukonb-w.css';
import '../../css/p/ppgi3vj8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="drxk66foz wm-k"/><path class="toaaljiww wm-shadow"/><path class="v2ukonb-w wm-k"/><path class="ppgi3vj8t wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-pin-engrave" {...props}></Icon>
