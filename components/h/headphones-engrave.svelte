<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i09dd_iqf.css';
import '../../css/k/kxbkcp9wd.css';
import '../../css/v/v3dbaokhc.css';
import '../../css/r/r0v6itbzy.css';
import '../../css/l/ltpyfabni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i09dd_iqf wm-k"/><path class="kxbkcp9wd wm-a"/><path class="v3dbaokhc wm-shadow"/><path class="r0v6itbzy wm-a"/><path class="ltpyfabni wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:headphones-engrave" {...props}></Icon>
