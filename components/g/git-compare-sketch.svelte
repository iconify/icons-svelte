<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cx7y8abax.css';
import '../../css/y/y3ln0db1m.css';
import '../../css/m/m928-m55s.css';
import '../../css/i/imwl13zcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cx7y8abax wm-k"/><path class="wm-k y3ln0db1m"/><path class="m928-m55s wm-k"/><path class="imwl13zcx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-compare-sketch" {...props}></Icon>
