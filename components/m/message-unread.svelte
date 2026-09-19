<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c_4rwbbkx.css';
import '../../css/i/iq4t2p2xt.css';
import '../../css/f/fulwhhb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="c_4rwbbkx"/><path class="iq4t2p2xt"/><circle class="fulwhhb_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:message-unread" {...props}></Icon>
