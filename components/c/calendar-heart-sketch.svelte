<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w6cbm5j2m.css';
import '../../css/p/pi1r4w0tu.css';
import '../../css/l/l18g6rvik.css';
import '../../css/f/fpb6z7hji.css';
import '../../css/k/k0pmgqbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w6cbm5j2m"/><path class="pi1r4w0tu wm-k"/><path class="l18g6rvik wm-a"/><path class="fpb6z7hji wm-k"/><path class="k0pmgqbjw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-heart-sketch" {...props}></Icon>
