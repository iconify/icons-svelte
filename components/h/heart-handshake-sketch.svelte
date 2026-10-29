<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/le3zaacjn.css';
import '../../css/e/elo-e5bqd.css';
import '../../css/b/b3jn5db8t.css';
import '../../css/n/nsalac6yh.css';
import '../../css/t/t6nv7kuam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="le3zaacjn"/><path class="elo-e5bqd wm-k"/><path class="b3jn5db8t wm-k"/><path class="nsalac6yh wm-a"/><path class="t6nv7kuam wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-handshake-sketch" {...props}></Icon>
