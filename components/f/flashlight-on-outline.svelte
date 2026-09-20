<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qrv48pbgw.css';
import '../../css/k/kv3pi7b2z.css';
import '../../css/h/hiflofblr.css';
import '../../css/l/lmmiwvbbm.css';
import '../../css/x/xwcqrabbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qrv48pbgw"/><path clip-rule="evenodd" class="kv3pi7b2z"/><path class="hiflofblr"/><path class="lmmiwvbbm"/><path class="xwcqrabbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flashlight-on-outline" {...props}></Icon>
